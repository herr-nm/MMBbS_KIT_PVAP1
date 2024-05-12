---
marp: true
theme: default
class: 
  - lead
  - invert
---

![bg left 120%](AsymmetrischeVerschlüsselung.png)

# Asymmetrische Verschlüsselung
##  OpenSSL

Alice und Bob's sicherer Datenaustausch

---

## Was ist asymmetrische Verschlüsselung?

![bg right:40% 150%](Keys.png)

- **Verschlüsselungsverfahren**, bei dem Schlüsselpaare verwendet werden
  -  öffentlicher Schlüssel
  -  privater Schlüssel
- **Einsatzgebiete:**
  - Sichere Datenübertragung
  - digitale Signaturen
  - Authentifizierung

---

## Vor- und Nachteile asymmetrischer Verschlüsselung

![bg right:40% 150%](Keys.png)

- **Vorteile:**
  - Sicherer Austausch von Informationen ohne vorherigen Austausch von Passwörtern
  - Ermöglicht die digitale Signatur von Daten (Authentifizierung & Integrität)
- **Nachteil:**
  - Rechenaufwand bei Ver- und Entschlüsselung
  - Aufwand zur Verwaltung von Schlüsseln

---

## Schlüsselgenerierung durch Alice

![bg right:33%](GenerateKey.png)

```bash
# Generiere RSA Schlüsselpaar für Alice
openssl genrsa -out alice_private.pem 2048
openssl rsa -in alice_private.pem -pubout -out alice_public.pem
```

---

## Schlüsselgenerierung durch Bob

![bg right:33%](GenerateKey.png)

```bash
# Generiere RSA Schlüsselpaar für Bob
openssl genrsa -out bob_private.pem 2048
openssl rsa -in bob_private.pem -pubout -out bob_public.pem
```

---

## Schlüsselaustausch

![bg left:60% 170%](Alice&Bob.png)

- **Alice sendet ihren öffentlichen Schlüssel an Bob**
- **Bob sendet seinen öffentlichen Schlüssel an Alice**

**Mittels sicherer Methode, z.B. über einen verschlüsselten Kanal.**

---

## Dateiverschlüsselung und Übertragung von Alice zu Bob

![bg right:33% 170%](KeyExchange.png)

```bash
# Alice verschlüsselt die Datei
openssl rsautl -encrypt -inkey bob_public.pem -pubin -in geheim.txt -out geheim_encrypted.txt

# Alice überträgt die verschlüsselte Datei an Bob mittels SCP
scp geheim_encrypted.txt bob@bobhost:/pfad/zu/bobs/ordner
```

---

## Dateientschlüsselung bei Bob

![bg left:33% 170%](SchlossOpen.png)


```bash
# Bob entschlüsselt die Datei
openssl rsautl -decrypt -inkey bob_private.pem -in geheim_encrypted.txt -out geheim_decrypted.txt