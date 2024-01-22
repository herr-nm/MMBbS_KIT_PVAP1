# IT-Sicherheit

## Grundlagen der Informationssicherheit anwenden

### Arbeitsauftrag - Dimensionen der Informationssicherheit unterscheiden

#### Aufgabe 1

Das Schutzziel "Vertraulichkeit" bedeutet, dass Informationen vor unbefugtem Zugriff oder Offenlegung geschützt werden sollen. Ziel ist es sicherzustellen, dass nur autorisierte Personen oder Systeme auf sensible Daten zugreifen können.

Beispiel: Ein Unternehmen speichert Kundeninformationen, einschließlich persönlicher Daten und finanzieller Informationen. Um die Vertraulichkeit zu gewährleisten, sollten nur autorisierte Mitarbeiter mit entsprechenden Zugriffsrechten auf diese sensiblen Daten zugreifen können, um Datenschutz und Privatsphäre zu gewährleisten.

#### Aufgabe 2

Das Schutzziel "Integrität" zielt darauf ab, sicherzustellen, dass Informationen unverändert und korrekt bleiben. Es geht darum, Manipulationen oder unautorisierte Änderungen an Daten zu verhindern.

Beispiel: Eine Bankdatenbank enthält Transaktionsaufzeichnungen. Um die Integrität zu wahren, müssen Mechanismen implementiert werden, die sicherstellen, dass keine unautorisierten Änderungen an den Transaktionsdaten vorgenommen werden können, um so die Genauigkeit und Zuverlässigkeit der Daten zu gewährleisten.

#### Aufgabe 3

Das Schutzziel "Verfügbarkeit" bedeutet, dass Informationen und Systeme stets verfügbar sein sollten, wenn sie benötigt werden. Ziel ist es, den Zugriff auf Informationen und Dienste sicherzustellen, ohne dabei durch unautorisierte Einflüsse oder Ausfälle beeinträchtigt zu werden.

Beispiel: Ein E-Commerce-Unternehmen muss sicherstellen, dass seine Website ständig verfügbar ist, damit Kunden jederzeit online einkaufen können. Maßnahmen zur Redundanz und Disaster Recovery können dazu beitragen, die Verfügbarkeit sicherzustellen.

#### Aufgabe 4

**Vertraulichkeit:**
   - Implementierung von Benutzerzugriffskontrollen auf dem Convertible-Laptop, um sicherzustellen, dass nur autorisierte Benutzer auf die darauf gespeicherten sensiblen Geschäftsdaten zugreifen können.
   - Verschlüsselung von Daten auf dem Laptop, um sicherzustellen, dass selbst bei physischem Diebstahl der Datenzugriff erschwert wird.

**Integrität:**
   - Einrichtung von Mechanismen zur Überprüfung der Datei- und Systemintegrität, um sicherzustellen, dass keine unbemerkten Änderungen an Dateien oder Einstellungen vorgenommen werden.
   - Implementierung von Sicherheitsrichtlinien, die sicherstellen, dass nur autorisierte Softwareinstallationen und Konfigurationsänderungen erlaubt sind.

**Verfügbarkeit:**
   - Implementierung von Backup- und Wiederherstellungsprozessen, um sicherzustellen, dass im Falle eines Geräteausfalls die Daten wiederhergestellt und das System schnell wieder in Betrieb genommen werden kann.
   - Überwachung der Netzwerkkonnektivität und Remote-Unterstützungsmöglichkeiten, um sicherzustellen, dass der Außendienstmitarbeiter bei Problemen schnell technische Unterstützung erhalten kann und die Arbeitsfähigkeit des Convertible-Laptops gewährleistet ist.

### Arbeitsauftrag - Angriffsszenarien einordnen

#### Aufgabe 1

- **Viren:** Selbstreplizierende schädliche Software, die sich an legitime Programme anhängt und sich so verbreitet.
- **Würmer:** Eigenständige, sich selbst verbreitende Programme, die Netzwerke infizieren und oft dazu verwendet werden, Schadcode zu verbreiten.
- **Trojaner:** Täuscht vor, nützliche Software zu sein, während sie heimlich schädliche Funktionen ausführt, oft durch Hintertüren für Angreifer.
- **Ransomware:** Schädliche Software, die Dateien oder Systeme verschlüsselt und Lösegeld verlangt, um die Daten wiederherzustellen.
- **Phishing:** Täuschung von Personen, um vertrauliche Informationen preiszugeben, indem gefälschte Kommunikation oder Websites genutzt werden.
- **Spoofing:** Vortäuschung einer falschen Identität oder Quelle, um eine legitime zu imitieren, z.B., indem gefälschte E-Mails von vertrauenswürdigen Absendern verschickt werden.
- **Spam:** Unverlangte Massen-E-Mails oder Nachrichten, oft für betrügerische Zwecke.
 **Spyware:** Software, die heimlich Informationen über einen Benutzer sammelt und an externe Quellen übermittelt.
- **Adware:** Anzeigenunterstützte Software, die unerwünschte Anzeigen auf dem Computer des Benutzers anzeigt, oft mit der Absicht, Einnahmen für den Angreifer zu generieren.
- **DDoS-Attacken:** Überflutung eines Netzwerks oder einer Website mit Traffic, um sie unzugänglich zu machen.
- **APT-Attacken (Advanced Persistent Threats):** Langfristige, zielgerichtete Angriffe, bei denen Angreifer unauffällig und beharrlich versuchen, in Netzwerke einzudringen, um sensible Informationen zu stehlen.

#### Aufgabe 2

 1. **Infektion:** Ransomware gelangt durch Phishing-E-Mails, infizierte Websites oder verwundbare Software ins Unternehmensnetzwerk.
 2. **Übernahme des Verzeichnisdienstes:** Versuch der Übernahme des Verzeichnisdienstes, um dort registrierte Backupserver zu finden und die Backups zu kompromittieren.
 3. **Download der Datenbestände:** Datenbestände werden heruntergeladen, um als weiteres Druckmittel die Veröffentlichung der Daten bei Nicht-Zahlung zu erhalten.
 4. **Verschlüsselung:** Die Ransomware verschlüsselt Dateien auf infizierten Systemen, macht sie unzugänglich.
 5. **Lösegeldforderung:** Die Angreifer fordern Lösegeld und drohen mit dauerhaftem Datenverlust oder Veröffentlichung sensibler Informationen.
 6. **Kommunikation:** Die Opfer erhalten Anweisungen zur Zahlung des Lösegelds, oft in Kryptowährung. Oftmals werden Beweis-Dateien angeboten, um zu sehen, dass die Angreifer wirklich in der Lage sind die Daten zu entschlüsseln. Ebenfalls ist oftmals ein gesamtes Datenverzeichnis der erbeuteten Daten verfügbar, um den Schaden einschätzen zu können (aus Angreifersicht zeigen, dass es ernst ist / aus Opfersicht wichtig für realistische Einschätzung des Angriffs sowie zur Information der Betroffenen).
 7. **Entschlüsselung (optional):** Nach Zahlung des Lösegelds liefern die Angreifer den Entschlüsselungsschlüssel (nicht immer garantiert und nicht empfohlen).

#### Aufgabe 3

- **Isolierung:** Infizierte Systeme vom Netzwerk trennen.
- **Meldung:** Vorfall den Behörden und ggf. Kunden melden (je nach Datenschutzbestimmungen).
- **Lösegeldzahlung:** Wird oft nicht empfohlen, da dies keine Garantie für die Datenwiederherstellung bietet und kriminelle Aktivitäten unterstützen kann.
- **Wiederherstellung:** Daten aus Backups wiederherstellen.
- **Rechtliche Schritte:** Zusammenarbeit mit Strafverfolgungsbehörden und Einhaltung von Datenschutzbestimmungen.

#### Aufgabe 4

 - **Backup-Strategien:** Regelmäßige Backups und Tests der Wiederherstellungsfähigkeit implementieren.
 - **Sicherheitsschulungen:** Mitarbeiter auf Phishing und sicheres Verhalten schulen.
 - **Aktualisierte Software:** Software und Systeme regelmäßig aktualisieren, um Sicherheitslücken zu schließen.
 - **Netzwerksicherheit:** Firewalls, Intrusion Detection/Prevention Systeme einsetzen.
 - **Notfallpläne:** Erstellung von Notfallplänen für den Umgang mit Ransomware-Angriffen. Dabei für produzierende Unternehmen die schnelle Aufnahme der Produktion im Fokus haben (die zeitlich aktuellen Daten sind dafür zu priorisieren).

#### Aufgabe 5

**Ablauf einer DDoS-Attacke:**
   1. **Überlastung:** Angreifer überfluten das Ziel mit einer großen Anzahl von Anfragen.
   2. **Serverüberlastung:** Die Zielserver können die große Anzahl von Anfragen nicht bewältigen, was zu Ausfällen führt.
   3. **Dienstunzugänglichkeit:** Die Dienste des Ziels stehen nicht mehr zur Verfügung.

**Gegenmaßnahmen:**
   - **DDoS-Schutzdienste:** Verwendung von Diensten, die den eingehenden Traffic filtern und schädliche Anfragen blockieren können.
   - **Lastenausgleich:** Verteilung des Traffics auf mehrere Server, um Überlastungen zu verhindern.
   - **Netzwerkinfrastruktur optimieren:** Implementierung von Technologien wie Content Delivery Networks (CDNs) zur effizienten Verteilung von Inhalten.
   - **Frühzeitige Erkennung:** Überwachung des Netzwerkverkehrs, um Anomalien frühzeitig zu erkennen und Gegenmaßnahmen zu ergreifen.

### Arbeitsauftrag - Grundlagen der Computersicherheit einhalten

#### Aufgabe 1

- **Länge:** Ein sicheres Passwort sollte ausreichend lang sein, üblicherweise mindestens 12 Zeichen.
- **Komplexität:** Verwenden Sie eine Kombination aus Groß- und Kleinbuchstaben, Zahlen und Sonderzeichen.
- **Einzigartigkeit:** Vermeiden Sie leicht erratbare Informationen wie Namen, Geburtsdaten oder Wörter aus dem Wörterbuch.
- **Regelmäßige Aktualisierung:** Ändern Sie Ihr Passwort in regelmäßigen Abständen (die auch etwas größer sein können), um die Sicherheit zu erhöhen.
- **Keine Wiederholungen:** Vermeiden Sie die Verwendung von bereits verwendeten Passwörtern für verschiedene Konten.

#### Aufgabe 2

Die 2-Faktor-Authentifizierung (2FA) ist eine Methode zur Sicherung von Konten, die auf zwei unabhängigen Bestätigungsfaktoren basiert. Die zwei Faktoren sind in der Regel:

1. **Etwas, das Sie wissen:** Zum Beispiel Ihr Passwort oder PIN.
2. **Etwas, das Sie besitzen:** Dies kann ein physisches Gerät wie Ihr Smartphone oder eine Sicherheitstoken sein.

Die Idee ist, dass selbst wenn ein Angreifer Ihr Passwort kennt, er immer noch den zweiten Faktor benötigt, um Zugriff zu erhalten.

#### Aufgabe 3

1. **Registrierung:** Der Benutzer meldet sich bei einem Dienst an und aktiviert die 2FA-Option.
2. **Gerät verbinden:** Das Gerät des Benutzers wird mit dem Dienst verbunden, normalerweise durch Scannen eines QR-Codes.
3. **Erzeugung von TOTP-Codes:** Eine TOTP-App auf dem Gerät generiert zeitbasierte Einmalpasswörter (TOTP-Codes).
4. **Eingabe des Codes:** Bei der Anmeldung gibt der Benutzer neben seinem Passwort auch den aktuellen TOTP-Code ein.
5. **Zeitbasierte Synchronisation:** Der Dienst und die TOTP-App sind zeitsynchronisiert, um sicherzustellen, dass der generierte Code korrekt ist.

#### Aufgabe 4

**Vorteile der biometrischen 2FA:**
- **Bequemlichkeit:** Biometrische Daten wie Fingerabdrücke oder Gesichtserkennung sind für den Benutzer bequem und erfordern keine zusätzlichen Passwörter oder Codes.
- **Hohe Genauigkeit:** Biometrische Merkmale sind in der Regel eindeutig und schwer zu fälschen, was die Sicherheit erhöht.

**Nachteile der biometrischen 2FA:**
- **Datenschutzbedenken:** Die Speicherung biometrischer Daten kann Datenschutzbedenken hervorrufen, insbesondere wenn diese in zentralen Datenbanken gespeichert sind.
- **Fälschungsmöglichkeiten:** Während biometrische Merkmale schwer zu fälschen sind, gibt es dennoch Möglichkeiten zur Überlistung, z. B. durch Fingerabdruckkopien oder Gesichtsimitationen.
- **Nicht änderbar:** Im Gegensatz zu Passwörtern können biometrische Merkmale nicht einfach geändert werden. Wenn sie einmal kompromittiert sind, bleibt dies eine dauerhafte Sicherheitslücke.

### Arbeitsauftrag - Technisch-organisatorische Maßnahmen anwenden

#### Aufgabe 1

Technisch-organisatorische Maßnahmen (TOM) sind Sicherheitsvorkehrungen, die sowohl technische als auch organisatorische Aspekte berücksichtigen, um die Sicherheit von Informationssystemen und Daten zu gewährleisten. Diese Maßnahmen dienen dazu, Risiken zu minimieren, Schutzmechanismen zu implementieren und die Verfügbarkeit, Integrität und Vertraulichkeit von Informationen sicherzustellen. Technisch-organisatorische Maßnahmen können beispielsweise Richtlinien, Prozesse, Schulungen, Zugriffskontrollen, Verschlüsselungstechnologien, Firewalls und andere Sicherheitsinfrastrukturen umfassen.

#### Aufgabe 2

- **Zugriffskontrolle:** Begrenzung des physischen Zugangs zum Serverraum durch biometrische Authentifizierung, Schlüsselkarten oder andere Zugangskontrollsysteme. Zudem sollten strenge Zugriffsrichtlinien für autorisiertes Personal festgelegt werden.
- **Videoüberwachung:** Installation von Überwachungskameras im Serverraum, um unbefugten Zugriff zu überwachen und aufzuzeichnen.
- **Brandschutzmaßnahmen:** Implementierung von Brandmeldesystemen, automatischen Feuerlöschanlagen und anderen Brandschutzvorkehrungen, um die physische Sicherheit des Serverraums zu gewährleisten.
- **Klimatisierung:** Kontrolle der Temperatur und Luftfeuchtigkeit im Serverraum, um optimale Bedingungen für die Serverhardware sicherzustellen und Überhitzung zu verhindern.
- **Stromversorgung:** Einsatz von unterbrechungsfreien Stromversorgungen (USV) und Generatoren, um einen kontinuierlichen Betrieb der Server bei Stromausfällen zu gewährleisten.
- **Alarmierungssysteme:** Einrichtung von Alarmen bei ungewöhnlichen Aktivitäten, wie zum Beispiel unbefugten Zutritt oder Temperaturabweichungen.
- **Dokumentation und Schulung:** Erstellung von klaren Richtlinien und Prozeduren für den Zugang zum Serverraum sowie Schulungen für Mitarbeiter, um sicherzustellen, dass alle Sicherheitsmaßnahmen bekannt sind und eingehalten werden.
- **Regelmäßige Überprüfungen und Audits:** Durchführung regelmäßiger Sicherheitsüberprüfungen und Audits, um sicherzustellen, dass die etablierten Sicherheitsmaßnahmen wirksam sind und den aktuellen Bedrohungen standhalten können.

#### Aufgabe 3

- **Firewalls:** Konfiguration und Einsatz von Firewalls, um den Netzwerkverkehr zu überwachen und unerwünschten Datenverkehr zu blockieren.
- **Intrusion Detection/Prevention System (IDS/IPS):** Einrichtung von Systemen zur Erkennung und Prävention von Eindringversuchen, um unautorisierte Zugriffsversuche zu erkennen und zu blockieren.
- **Verschlüsselung:** Verschlüsselung von Daten auf dem Server, insbesondere bei der Übertragung sensibler Informationen über das Netzwerk (z.B., HTTPS für Webanwendungen).
- **Patches und Updates:** Regelmäßige Aktualisierung von Betriebssystemen, Anwendungen und anderen Softwarekomponenten, um bekannte Sicherheitslücken zu schließen.
- **Zugriffskontrolle:** Implementierung von strikten Zugriffskontrollen und Berechtigungen für Benutzer und Prozesse, um den Zugang zu sensiblen Daten zu beschränken.
- **Authentifizierungsmethoden:** Verwendung von starken Authentifizierungsmethoden wie Multi-Faktor-Authentifizierung (MFA), um die Sicherheit von Zugriffen auf den Server zu erhöhen.
- **Logging und Überwachung:** Einrichtung von Protokollierungssystemen, um Aktivitäten auf dem Server zu überwachen und verdächtige Aktivitäten frühzeitig zu erkennen.
- **Antivirus-Software:** Installation von Antivirus-Programmen, um schädliche Software zu erkennen und zu entfernen.
- **Backup-Strategien:** Implementierung von regelmäßigen Backup-Strategien, um im Falle eines Datenverlusts oder einer Systembeschädigung eine Wiederherstellung zu ermöglichen.
- **Netzwerksicherheit:** Konfiguration von Netzwerksicherheitsmaßnahmen wie VLANs (Virtual Local Area Networks) und sichere Konfiguration von Netzwerkprotokollen.
- **Ressourcenüberwachung:** Überwachung der Serverressourcen wie CPU-Auslastung, Speicherverbrauch und Netzwerkauslastung, um Engpässe oder Anomalien frühzeitig zu identifizieren.
- **Richtlinien und Schulungen:** Erstellung von Sicherheitsrichtlinien und Durchführung von Schulungen für das Serverpersonal, um bewusstes Handeln im Sinne der Informationssicherheit zu fördern.

## IT-Grundschutz planen

### Arbeitsauftrag - IT-Grundschutz planen

#### Aufgabe 1

Die Norm, die die Gewährleistung der IT-Sicherheit und den Aufbau eines IT-Sicherheitsmanagementsystems betrifft, ist die ISO/IEC 27001. Diese Norm gehört zur ISO/IEC 27000-Familie, die sich mit Informationssicherheitsmanagement befasst. Die ISO/IEC 27001 spezifiziert die Anforderungen für das Einrichten, Umsetzen, Aufrechterhalten und ständige Verbessern eines Informationssicherheitsmanagementsystems (ISMS). Sie bietet einen systematischen Ansatz zur Verwaltung sensibler Unternehmensinformationen und zur Gewährleistung ihrer Integrität, Vertraulichkeit und Verfügbarkeit.

#### Aufgabe 2

Der PDCA-Zyklus steht für Plan-Do-Check-Act und ist ein zyklischer Ansatz zur kontinuierlichen Verbesserung. Im Kontext eines IT-Sicherheitssystems, insbesondere eines Informationssicherheitsmanagementsystems (ISMS) nach ISO/IEC 27001, könnten die Schritte wie folgt aussehen:

- **Plan (Planen):**
   - Festlegung der Sicherheitsziele und -politik.
   - Durchführung einer Risikobewertung und Definition von Maßnahmen zur Risikominderung.
   - Entwicklung und Implementierung von Prozessen und Verfahren für das IT-Sicherheitsmanagement.
- **Do (Umsetzen):**
   - Implementierung der geplanten Maßnahmen.
   - Schulung der Mitarbeiter bezüglich Sicherheitsrichtlinien und Verfahren.
   - Einführung von Sicherheitskontrollen und -technologien.
- **Check (Überprüfen):**
   - Durchführung von regelmäßigen Audits und Überwachung der Sicherheitsleistung.
   - Überprüfung von Sicherheitsvorfällen und Problemen.
   - Auswertung von Metriken und Leistungskennzahlen im Hinblick auf die Sicherheitsziele.
- **Act (Handeln):**
   - Initiierung von Korrekturmaßnahmen für identifizierte Schwachstellen oder Verbesserungspotenziale.
   - Anpassung von Sicherheitsrichtlinien und -prozessen basierend auf den Überprüfungsergebnissen.
   - Einleiten von vorbeugenden Maßnahmen, um zukünftige Sicherheitsprobleme zu verhindern.

#### Aufgabe 3

**Prozess-Bausteine:**

- ISMS: Sicherheitsmanagement
  - z.B. ISMS.1 Sicherheitsmanagement
- ORP: Organisation und Personal
  - z.B. ORP.1 Organisation
  - z.B. ORP.2 Personal
  - z.B. ORP.3 Sensibilisierung und Schulung
  - z.B. ORP.4 Identitäts- und Berechtigungsmanagement
- CON: Konzeption und Vorgehensweisen
  - z.B. CON.1 Kryptokonzept
  - z.B. CON.2 Datenschutz
  - z.B. CON.3 Datensicherungskonzept
  - z.B. CON.4 Auswahl und Einsatz von Standardsoftware
  - z.B. CON.5 Entwicklung und Einsatz von Allgemeinen Anwendungen
  - z.B. CON.6 Löschen und Vernichten
- OPS: Betrieb, aufgeteilt in die vier Teilschichten Eigener IT-Betrieb, Betrieb von Dritten, Betrieb für Dritte und Betriebliche Aspekte
  - z.B. OPS.1.1.2 Ordnungsgemäße IT-Administration
  - z.B. OPS.1.1.3 Patch- und Änderungsmanagement
  - z.B. OPS.1.1.4 Schutz vor Schadprogrammen, 
  - z.B. OPS.1.1.5 Protokollierung, 
  - z.B. OPS.2.1 Outsourcing für Kunden, 
  - z.B. OPS.2.4 Fernwartung
- DER: Detektion und Reaktion
  - z.B. DER.1 Detektion von sicherheitsrelevanten Ereignissen, D
  - z.B. DER.2.1 Behandlung von Sicherheitsvorfällen
  - z.B. DER2.2 Vorsorge für die IT-Forensik
  - z.B. DER.3.1 Audits und Revisionen
  - z.B. DER.4 Notfallmanagement

**System-Bausteine:**

- APP: Anwendungen
  - z.B. APP.1.1 Office Produkte, 
  - z.B. APP.1.2 Webbrowser, 
  - z.B. APP.3.2 Webserver, 
  - z.B. APP.5.1 Allgemeine Groupware, 
  - z.B. APP.5.2 Microsoft Exchange und Outlook
- SYS: IT-Systeme
  - z.B. SYS.1.1 Allgemeiner Server, 
  - z.B. SYS.1.2.2 Windows Server 2012, 
  - z.B. SYS.1.5 Virtualisierung
  - z.B. SYS.2.3 Client unter Windows 10
  - z.B. SYS.3.1 Laptops
  - z.B. SYS 3.2.1 Allgemeine Smartphones und Tablets
- IND: Industrielle IT
  - z.B. IND.1 Betriebs- und Steuerungstechnik
- NET: Netze und Kommunikation
  - z.B. NET.1.1 Netzarchitektur und Design, 
  - z.B. NET.1.2 Netzmanagement, 
  - z.B. NET.2.1 WLAN-Betrieb, 
  - z.B. NET.2.2 WLAN-Nutzung
  - z.B. NET.3.1 Router und Switches
  - z.B. NET.3.2 Firewall
- INF: Infrastruktur
  - z.B. INF.1 Allgemeines Gebäude
  - z.B. INF.2 Rechenzentrum sowie Serverraum
  - z.B. INF.7 Büroarbeitsplatz
  - z.B. INF.8 Häuslicher Arbeitsplatz

#### Aufgabe 4

1. **Schutzbedarfsfeststellung:**
   - Identifikation der zu schützenden Informationen und Datentypen (z.B., Produktbezogene Dateien, Kundenanfragen, Geschäftsbriefe).
   - Einstufung der Schutzbedarfskategorien (niedrig, normal, hoch, sehr hoch) für die identifizierten Informationen.

2. **Anwendung des IT-Grundschutz-Kompendiums:**
   - Nutzung des IT-Grundschutz-Kompendiums, um die notwendigen Maßnahmen für den identifizierten Schutzbedarf zu ermitteln.
   - Auswahl von Bausteinen und Maßnahmen aus dem Kompendium, die für den Schutz der spezifischen Informationen relevant sind. In diesem Fall [BSI SYS.1.8: Speicherlösungen](https://www.bsi.bund.de/SharedDocs/Downloads/DE/BSI/Grundschutz/Kompendium_Einzel_PDFs_2021/07_SYS_IT_Systeme/SYS_1_8_Speicherloesungen_Edition_2021.pdf?__blob=publicationFile&v=2).

3. **Risikoanalyse:**
   - Identifikation potenzieller Risiken und Bedrohungen für den Datenspeicher der Vertriebsabteilung.
   - Bewertung der Eintrittswahrscheinlichkeit und der möglichen Auswirkungen der identifizierten Risiken.

4. **Maßnahmenplanung:**
   - Entwicklung eines Maßnahmenplans zur Minimierung der Risiken.
   - Auswahl und Umsetzung von Sicherheitsmaßnahmen, die auf den identifizierten Schutzbedarf und die ermittelten Risiken abgestimmt sind.

5. **Überwachung und Anpassung:**
   - Kontinuierliche Überwachung der Wirksamkeit der implementierten Maßnahmen.
   - Anpassung der Sicherheitsmaßnahmen bei veränderten Bedrohungsszenarien oder Anforderungen.

#### Aufgabe 5

Die Schutzbedarfskategorien nach BSI-Standard unterscheiden sich in den Schutzzielen und den erwarteten Auswirkungen von Beeinträchtigungen. Hier sind die Kategorien mit Beispielen:

- **Niedrig:**
   - **Schutzziel:** Schutz vor Beeinträchtigungen mit geringen Auswirkungen.
   - **Beispiel:** Allgemeine Unternehmensinformationen, die öffentlich verfügbar sind.
- **Normal:**
   - **Schutzziel:** Schutz vor Beeinträchtigungen mit spürbaren Auswirkungen.
   - **Beispiel:** Kundenkontaktinformationen, Standardproduktinformationen.
- **Hoch:**
   - **Schutzziel:** Schutz vor schwerwiegenden Auswirkungen auf die Geschäftsprozesse.
   - **Beispiel:** Vertrauliche Geschäftsbriefe, detaillierte Produktentwicklungspläne.
- **Sehr Hoch:**
   - **Schutzziel:** Schutz vor schwerwiegenden Auswirkungen auf das Unternehmen oder die öffentliche Sicherheit. Verstoß gegen Gesetze, Vorschriften oder Verträge.
   - **Beispiel:** Forschungsergebnisse, Strategiepläne, hochsensible Kundendaten.

## DSGVO-konform handeln

### Arbeitsauftrag - DSGVO-konform handeln

#### Aufgabe 1

Personenbezogene Daten sind Informationen, die sich auf eine identifizierte oder identifizierbare natürliche Person beziehen. Dazu gehören alle Daten, die direkt oder indirekt Rückschlüsse auf eine bestimmte Person zulassen, wie beispielsweise Name, Adresse, Telefonnummer, E-Mail-Adresse, Sozialversicherungsnummer, Standortdaten oder IP-Adressen.

#### Aufgabe 2

Besonders schützenswerte personenbezogene Daten unterscheiden sich von allgemeinen personenbezogenen Daten durch ihre Sensibilität und das damit verbundene höhere Schutzbedürfnis. Zu den besonders schützenswerten Daten gehören Informationen über die ethnische Herkunft, politische Meinungen, religiöse oder weltanschauliche Überzeugungen, Gewerkschaftszugehörigkeit, Gesundheitsdaten, genetische Daten, biometrische Daten sowie Daten zum Sexualleben oder der sexuellen Orientierung.

#### Aufgabe 3

Die Aussage des Mitarbeiters des Personaldienstleisters ist korrekt im Hinblick auf Datenschutz. Die Nennung des durchschnittlichen Gehalts einer spezifischen Mitarbeitergruppe könnte dazu führen, dass einzelne Personen identifiziert werden könnten. Dies würde gegen die Grundsätze des Datenschutzes verstoßen, insbesondere gegen das Prinzip der Datensparsamkeit.

#### Aufgabe 4

Als Kunde eines Onlineshops haben Betroffene verschiedene Rechte im Zusammenhang mit ihren personenbezogenen Daten. Zu den wichtigsten gehören das Recht auf Auskunft über die gespeicherten Daten, das Recht auf Berichtigung fehlerhafter Daten, das Recht auf Löschung ("Recht auf Vergessenwerden"), das Recht auf Datenübertragbarkeit, das Widerspruchsrecht gegen bestimmte Datenverarbeitungen sowie das Recht, nicht einer ausschließlich auf automatisierter Verarbeitung beruhenden Entscheidung unterworfen zu werden.

#### Aufgabe 5

Im Falle eines DSGVO-Verstoßes oder eines Cyberangriffs mit Erbeutung von Kundendaten ergeben sich für das betroffene Unternehmen verschiedene Verpflichtungen. Dazu gehören die unverzügliche Benachrichtigung der Aufsichtsbehörde über den Datenschutzverstoß, die Information der betroffenen Personen über den Vorfall, die Dokumentation des Vorfalls sowie gegebenenfalls die Durchführung einer Datenschutz-Folgenabschätzung. Zudem können Geldbußen und Schadensersatzforderungen gegen das Unternehmen verhängt werden. Es ist wichtig, dass das betroffene Unternehmen angemessene Sicherheitsmaßnahmen trifft, um Datenschutzverletzungen zu verhindern.

#### Aufgabe 6

Identifizierbare Daten, pseudonymisierte Daten und anonyme Daten unterscheiden sich in ihrem Grad der Personenbeziehbarkeit:

- **Identifizierbare Daten:**
   - Identifizierbare Daten sind Informationen, die alleine oder in Verbindung mit anderen Daten dazu verwendet werden können, eine bestimmte Person direkt zu identifizieren.
   - Beispiele hierfür sind der vollständige Name, die Adresse oder die Sozialversicherungsnummer einer Person.
   - Solche Daten ermöglichen eine eindeutige Zuordnung zu einer identifizierbaren natürlichen Person.
- **Pseudonymisierte Daten:**
   - Pseudonymisierte Daten sind personenbezogene Daten, bei denen der direkte Bezug zu einer bestimmten Person durch die Verwendung eines Pseudonyms erschwert wird.
   - Dabei werden Identifikationsmerkmale durch ein Pseudonym ersetzt, sodass die Daten zwar noch einer Person zugeordnet werden können, aber der direkte Rückschluss erschwert wird.
   - Die Zuordnung erfordert zusätzliche Informationen, die separat aufbewahrt werden.
- **Anonyme Daten:**
   - Anonyme Daten sind Informationen, die so stark verfremdet oder aggregiert wurden, dass keine Möglichkeit mehr besteht, die Daten einer bestimmten Person zuzuordnen.
   - Selbst durch Kombination mit anderen Daten oder den Einsatz von zusätzlichen Analysemethoden ist keine Identifikation möglich.
   - Anonyme Daten unterliegen in vielen Rechtsordnungen nicht den Datenschutzregelungen, da sie keine personenbezogenen Informationen mehr darstellen.

## Abwehr von Angriffen planen

### Arbeitsauftrag - Abwehr von Angriffen planen

#### Aufgabe 1

- **Signaturerkennung:** Das Antiviren-Programm vergleicht Dateien und Programme auf dem Computer mit einer Datenbank bekannter Malware-Signaturen. Wenn eine Übereinstimmung gefunden wird, wird die Datei als schädlich identifiziert.
- **Heuristische Analyse:** Das Programm analysiert das Verhalten von Dateien und Programmen. Verdächtiges Verhalten, auch wenn keine genaue Signatur bekannt ist, kann auf eine Bedrohung hinweisen.
- **Verhaltensanalyse:** Fortschrittlichere Antiviren-Programme überwachen das Verhalten von Anwendungen in Echtzeit. Abweichungen von normalem Verhalten können auf eine Infektion hinweisen.
- **Sandboxing:** Einige Antiviren-Programme isolieren potenziell gefährliche Dateien in einer sicheren Umgebung (Sandbox) und beobachten deren Verhalten, um festzustellen, ob sie schädlich sind.
- **Automatische Updates:** Die Antiviren-Software aktualisiert regelmäßig ihre Signaturen und Datenbanken, um gegen neu auftretende Bedrohungen gewappnet zu sein.

#### Aufgabe 2

Eine portbasierte Firewall arbeitet auf Netzwerkschicht und entscheidet, ob Datenpakete zwischen verschiedenen Netzwerken passieren dürfen oder nicht. Die Funktionsweise umfasst:

- **Portfilterung:** Die Firewall überprüft die Ziel- und Quell-Ports der Datenpakete. Portnummern sind numerische Identifikatoren für bestimmte Dienste. Die Firewall kann Regeln haben, die den Datenverkehr basierend auf diesen Portnummern erlauben oder blockieren.
- **Zustandsbasierte Überwachung:** Die Firewall verfolgt den Zustand der Netzwerkverbindungen und erlaubt nur den Datenverkehr, der zu einer bestehenden, erlaubten Verbindung gehört. Dies erhöht die Sicherheit, da nur erwarteter und autorisierter Datenverkehr durchgelassen wird.
- **Protokollüberwachung:** Die Firewall kann bestimmte Netzwerkprotokolle überwachen und den Datenverkehr basierend auf diesen Protokollen steuern.
- **NAT (Network Address Translation):** Die Firewall kann NAT verwenden, um die internen Netzwerkadressen vor externen Netzwerken zu verbergen und den ausgehenden Datenverkehr zu verwalten.

#### Aufgabe 3

- **Paketinspektion auf Anwendungsebene:** DPI geht über traditionelle Firewall-Methoden hinaus, indem es den gesamten Inhalt der Datenpakete auf Anwendungsebene analysiert. Dies schließt die Überprüfung von Protokollen, Headerinformationen und dem eigentlichen Nutzdateninhalt ein.
- **Entschlüsselung von HTTPS-Traffic:** Da DPI den gesamten Inhalt der Pakete analysiert, kann es auch verschlüsselten HTTPS-Verkehr entschlüsseln, um den Inhalt zu inspizieren. Dies erfordert jedoch den Einsatz von Methoden wie SSL/TLS-Man-in-the-Middle (MitM)-Angriffen, bei denen die Firewall sich zwischen dem Benutzer und dem Server positioniert und den verschlüsselten Verkehr entschlüsselt, um ihn zu überprüfen.
- **Protokoll- und Anwendungserkennung:** DPI identifiziert nicht nur Ports und IP-Adressen, sondern auch die spezifischen Anwendungen und Protokolle, die für den Datenverkehr verwendet werden. Dies ermöglicht es, genauere Sicherheitsrichtlinien basierend auf Anwendungen zu erstellen.
- **Mustererkennung und Signaturen:** DPI sucht nach spezifischen Mustern oder Signaturen in den Datenpaketen, um schädliche Inhalte wie Viren, Malware oder verdächtige Aktivitäten zu identifizieren. Die Firewall kann dabei auf eine umfassende Datenbank von Signaturen zurückgreifen.
- **Content-Filtering:** Die Firewall kann den Zugriff auf bestimmte Arten von Inhalten basierend auf dem analysierten Inhalt blockieren oder erlauben. Dies umfasst die Filterung von Websites, Dateitypen oder spezifischem Content.
- **Zustandsbezogene Überwachung:** DPI kann den Zustand von Netzwerkverbindungen überwachen und sicherstellen, dass nur erwarteter und autorisierter Datenverkehr zugelassen wird. Dies trägt zur Erhöhung der Sicherheit bei.
- **Verschlüsselte HTTPS-Inspektion (SSL/TLS-Decryption):** Bei verschlüsseltem HTTPS-Verkehr setzt die Firewall möglicherweise SSL/TLS-Decryption ein. Hierbei wird der verschlüsselte Datenverkehr entschlüsselt, inspiziert und dann wieder verschlüsselt, bevor er weitergeleitet wird. Dies ermöglicht die Analyse des Inhalts, selbst wenn er über HTTPS übertragen wird.

#### Aufgabe 4

Die Entschlüsselung von HTTPS-Datenverkehr kann mit Datenschutz- und Compliance-Anforderungen in Konflikt stehen kann, und Organisationen müssen sicherstellen, dass sie dies unter Einhaltung der relevanten Gesetze und Vorschriften durchführen.

#### Aufgabe 5

- **Packet Sniffing:** Erfassen und analysieren Sie den Datenverkehr im Netzwerk, um Anomalien oder verdächtige Aktivitäten zu erkennen.
- **Log-Analyse:** Überwachen und analysieren Sie Logdateien von Netzwerkkomponenten, Betriebssystemen und Anwendungen auf ungewöhnliche Ereignisse.
- **Netzwerk-Scans:** Führen Sie regelmäßige Scans durch, um Schwachstellen und potenzielle Sicherheitslücken im Netzwerk zu identifizieren.
- **Intrusion Detection System (IDS):** Implementieren Sie ein IDS, das Anomalien und potenzielle Angriffe erkennt und Alarme auslöst.
- **Flow-Monitoring:** Überwachen Sie den Fluss von Datenpaketen im Netzwerk, um Muster und Abweichungen zu identifizieren.
- **Verhaltensanalyse:** Analysieren Sie das normale Verhalten des Netzwerks, um Anomalien oder ungewöhnliche Aktivitäten zu erkennen.

#### Aufgabe 6

- **Segmentierung:** VLANs ermöglichen die logische Segmentierung eines physischen Netzwerks in separate virtuelle Netzwerke. Dies hilft, den Datenverkehr zu isolieren und die Ausbreitung von Angriffen zu begrenzen.
- **Sicherheitszonen:** Durch die Zuweisung von VLANs zu bestimmten Sicherheitszonen können Sicherheitsrichtlinien und Zugriffskontrollen effektiv durchgesetzt werden.
- **Broadcast-Isolation:** VLANs reduzieren Broadcast-Domänen, wodurch die Auswirkungen von Broadcast-Stürmen minimiert werden und die Netzwerksicherheit verbessert wird.
- **Ressourcenisolierung:** Kritische Ressourcen können in separaten VLANs platziert werden, um den Zugriff zu beschränken und die Sicherheit zu erhöhen.
- **Einfachere Verwaltung:** Die Verwaltung von Netzwerkressourcen wird durch die Verwendung von VLANs vereinfacht, da Änderungen in einem VLAN die anderen Bereiche des Netzwerks nicht beeinträchtigen.

#### Aufgabe 7

- **Internet-facing Firewall:** Diese Firewall verbindet das interne Netzwerk über den Router mit dem Internet. Sie filtert den ein- und ausgehenden Datenverkehr und leitet den relevanten Datenverkehr zur DMZ weiter.
- **DMZ-Server:** In der DMZ platzierte Server, wie Webserver, E-Mail-Server oder öffentlich zugängliche Dienste, sind für den externen Verkehr zugänglich. Diese Server sind von den internen Ressourcen getrennt, um das interne Netzwerk vor direkten Angriffen zu schützen.
- **Internes Firewall-Gateway:** Dieses Firewall-Gateway trennt die DMZ von internen Netzwerken und sorgt für zusätzliche Sicherheit durch Regelwerke und Zugriffskontrollen.

Unterscheidung der Netzbereiche:

- **Interne Netzwerke (LAN):** Hier befinden sich die Unternehmensressourcen, Daten und Mitarbeitergeräte. Der Zugriff ist normalerweise auf autorisierte Benutzer beschränkt.
- **DMZ:** Diese Zone enthält öffentlich zugängliche Server und Dienste. Der Zugriff ist beschränkt, um sicherzustellen, dass externe Angriffe nicht direkt auf das interne Netzwerk zugreifen können.
- **Externes Netzwerk (Internet):** Das öffentliche Internet, von dem aus Datenverkehr in die DMZ und das interne Netzwerk geleitet wird.

## Verfügbarkeit sicherstellen

### Arbeitsauftrag - Unterbrechungsfreie Stromversorgung planen

#### Aufgabe 1

**Notstrom:**
- **Ziel:** Bereitstellung von elektrischer Energie während eines Stromausfalls, um den Betrieb für eine begrenzte Zeit aufrechtzuerhalten.
- **Realisierung:** Verwendung von Dieselgeneratoren oder anderen primären Energiequellen, die kontinuierlich elektrische Energie liefern können.

**Unterbrechungsfreie Stromversorgung (USV):**
- **Ziel:** Gewährleistung einer unterbrechungsfreien Stromversorgung, indem sie während eines Stromausfalls sofort auf interne Batterien umschaltet.
- **Realisierung:** Verwendung von Batterien, die kontinuierlich aufgeladen werden, während das Netzstrom verfügbar ist. Bei Stromausfall erfolgt der nahtlose Übergang auf die Batterieversorgung.

#### Aufgabe 2

Die Last ist permanent über die Batterien mit Wechselstrom versorgt. Der Wechselrichter wandelt die Batterie-Gleichspannung kontinuierlich in Wechselspannung um. Der Netzstrom wird kontinuierlich genutzt, um die Batterien aufzuladen. Bei einem Stromausfall schaltet die USV sofort auf Batteriebetrieb um, ohne eine Unterbrechung in der Stromversorgung zu verursachen.

#### Aufgabe 3

Der Netzstrom versorgt die angeschlossene Last und lädt gleichzeitig die Batterien über einen internen Laderegler auf. Bei einem Stromausfall schaltet die USV auf Batteriebetrieb um. Bei Spannungsschwankungen oder -störungen wird die Netzspannung durch den internen Wechselrichter korrigiert.

#### Aufgabe 4

Die Last wird normalerweise direkt vom Netzstrom versorgt. Die Batterien sind nicht ständig mit der Last verbunden, sondern nur im Falle eines Stromausfalls. Bei einem Ausfall schaltet die USV auf Batteriebetrieb um und versorgt die Last über den internen Wechselrichter.

#### Aufgabe 5

zu 1.:

- Autonomiezeit (in Stunden) = (Batteriekapazität in kWh) / (Leistungsaufnahme des Racks in kW)
- Autonomiezeit = 5 kWh / 2,5 kW = 2 Stunden = 120 Minuten

zu 2.:

- Neue Leistungsaufnahme = 2,5 kW - 1 kW = 1,5 kW
- Neue Autonomiezeit = 5 kWh / 1,5 kW = 3,33 Stunden = 199 Minuten

zu 3.:

- Gesamtzeit ohne Strom = 1 Stunde (Februar) + 2 Stunden (Oktober) + 2 Stunden (November) = 5 Stunden
- Verfügbarkeit = (365 Tage * 24 Stunden - Gesamtzeit ohne Strom) / (365 Tage * 24 Stunden) * 100%
- Verfügbarkeit = (8760 - 5) / 8760 * 100% = 99,94%

### Arbeitsauftrag - Backupverfahren anwenden

#### Aufgabe 1

- **Differenzielles Backup:** Sichert alle Daten, die seit dem letzten Vollbackup geändert wurden. Es beinhaltet nur die Unterschiede zwischen dem letzten Vollbackup und dem aktuellen Zustand.
- **Inkrementelles Backup:** Sichert nur die Daten, die seit dem letzten Backup (egal ob Voll- oder Inkrementell) hinzugefügt oder geändert wurden. Es nimmt nur die Änderungen seit dem letzten Backup auf. Ganz vorne in der Kette steht ein Vollbackup.

#### Aufgabe 2

- **Verständnis:** Unveränderliche Backups sind Sicherungskopien, die nach ihrer Erstellung nicht mehr geändert werden können.
- **Nutzung:** Diese Backups werden oft für die langfristige Aufbewahrung von Daten eingesetzt, um sicherzustellen, dass die gesicherten Informationen unverändert bleiben, insbesondere im Kontext von Compliance-Anforderungen. Unveränderbare Backups spielen außerdem eine entscheidende Rolle im Rahmen von Ransomware-Angriffen. In diesem Kontext sind unveränderliche Backups von großer Bedeutung, da sie als wirksame Schutzmaßnahme vor Datenverlust bei einem Angriff dienen können.

#### Aufgabe 3

- **3 Kopien der Daten:** Erstellen Sie mindestens drei Kopien Ihrer Daten, um Redundanz zu gewährleisten.
- **2 verschiedene Medientypen:** Verwenden Sie unterschiedliche Medientypen (z.B., Festplatten, Bänder, Cloud), um sich vor Ausfallrisiken zu schützen.
- **1 Kopie extern speichern:** Speichern Sie mindestens eine Kopie Ihrer Daten an einem externen Ort, um vor physischen Katastrophen zu schützen.

#### Aufgabe 4

- **Großvater:** Regelmäßige Vollbackups, typischerweise wöchentlich, die für eine längere Zeit aufbewahrt werden.
- **Vater:** Tägliche oder inkrementelle Backups, die über eine mittlere Zeitspanne aufbewahrt werden.
- **Sohn:** Häufige, inkrementelle Backups, die nur für kurze Zeiträume aufbewahrt werden.

Dieses Prinzip ermöglicht eine effiziente und langfristige Aufbewahrung von Backups bei gleichzeitiger Minimierung des Speicherplatzbedarfs.

#### Aufgabe 5

- **Verschlüsselung:** Verwenden Sie starke Verschlüsselung für Backup-Daten, um die Vertraulichkeit zu gewährleisten. Dies gilt insbesondere für cloudbasierte Backupverfahren.
- **Zugriffskontrolle:** Implementieren Sie strenge Zugriffskontrollen, um unbefugten Zugriff auf Backup-Dateien zu verhindern. Backup-Server sollten besonders geschützt und von Remote-Zugriffen mit Lese- und Löschrechten abgesehen werden. Der User, der befähigt ist, auf dem Backupserver zu schreiben sollte keine Berechtigung zum Löschen haben. Der "Master-Root-Admin" sollte bestenfalls gar nicht für Remoteverbindungen eingerichtet sein. 
- **Backup-Verfahren testen:** Führen Sie regelmäßige Tests von Wiederherstellungsverfahren durch, um sicherzustellen, dass Backups erfolgreich wiederhergestellt werden können. Oftmals wird leider erst im Fall eines Datenverlustes festgestellt, dass der Backup-Mechanismus an einer Stelle nicht funktioniert hat.

#### Aufgabe 6

- **Einwilligung:** Stellen Sie sicher, dass Sie die Einwilligung der Betroffenen für das Speichern ihrer Daten in der Cloud haben.
- **Datensicherheit:** Gewährleisten Sie, dass die Cloud-Plattform den erforderlichen Datenschutz- und Sicherheitsstandards entspricht.
- **Datentransparenz:** Informieren Sie die Nutzer darüber, wie und wo ihre Daten gespeichert und verarbeitet werden.

#### Aufgabe 7

Notfallwiederherstellung bezieht sich auf die Fähigkeit einer Organisation, nach schwerwiegenden Störungen oder Katastrophen den normalen Geschäftsbetrieb so schnell wie möglich wiederherzustellen.

Wenn Ihr Ausbildungsbetrieb zu den Unternehmen der kritischen Infrastruktur (KRITIS) zählt, werden ggf. weitere Maßnahmen notwendig sein.

- **Notfallwiederherstellungspläne:**
   - Erstellung von detaillierten Plänen, die den Prozess und die Verfahren zur Wiederherstellung von IT-Systemen im Falle eines Notfalls beschreiben.
   - Identifikation kritischer Systeme und Daten, die priorisiert wiederhergestellt werden sollten.
- **RTO und RPO:**
   - **Recovery Time Objective (RTO):** Die maximale tolerierbare Zeit, die benötigt wird, um einen bestimmten Service oder eine Anwendung nach einem Ausfall wiederherzustellen.
   - **Recovery Point Objective (RPO):** Der maximale akzeptable Datenverlust, der im Falle eines Notfalls toleriert werden kann.
- **Backup-Tests und Simulationen:**
   - Durchführung von regelmäßigen Tests und Simulationen von Notfallszenarien, um sicherzustellen, dass die Wiederherstellungspläne effektiv sind.
   - Identifizierung von Schwachstellen und kontinuierliche Verbesserung der Notfallwiederherstellungsstrategien.
- **Notfallwiederherstellungsteams:**
   - Benennung und Schulung von Notfallwiederherstellungsteams, die im Falle eines Notfalls die Verantwortung für die Umsetzung der Wiederherstellungspläne übernehmen.
   - Klare Zuweisung von Aufgaben und Verantwortlichkeiten im Team.
- **Sicherung von Notfallstandorten:**
   - Einrichtung von physischen oder virtuellen Notfallstandorten, an denen kritische Systeme und Daten im Notfall wiederhergestellt werden können.
   - Sicherstellung, dass die Notfallstandorte die erforderlichen Ressourcen und Infrastruktur für eine schnelle Wiederherstellung bereitstellen können.
- **Kommunikationsstrategien:**
   - Entwicklung von Kommunikationsstrategien, um interne und externe Stakeholder während eines Notfalls angemessen zu informieren.
   - Klare Kommunikationswege und Verfahren für den Informationsaustausch während der Notfallwiederherstellung.
- **Dokumentation:**
   - Umfassende Dokumentation aller Notfallwiederherstellungspläne, -verfahren und -tests, um eine einfache Überprüfung und Aktualisierung zu ermöglichen.
   - Einbeziehung von Inventarlisten, Konfigurationen und Kontaktdaten in die Dokumentation.

## Integrität gewährleisten

### Arbeitsauftrag - Integrität von Daten kontrollieren

#### Aufgabe 1

Eine Hash-Funktion ist ein mathematischer Algorithmus, der dazu dient, Daten jeder Größe in eine feste Länge von Zeichen, den sogenannten Hash-Wert, umzuwandeln. Dieser Hash-Wert ist ein eindeutiger, pseudozufälliger String, der charakteristisch für die ursprünglichen Daten ist. Hash-Funktionen sind so konzipiert, dass geringfügige Änderungen an den Daten zu völlig unterschiedlichen Hash-Werten führen.

Die Prüfung der Integrität von Daten mithilfe von Hash-Funktionen erfolgt in der Regel, indem der Sender einen Hash-Wert der Daten erstellt und diesen zusammen mit den Daten übermittelt. Der Empfänger kann dann denselben Hash-Algorithmus auf die empfangenen Daten anwenden und den generierten Hash-Wert mit dem vom Sender übermittelten Hash-Wert vergleichen. Stimmen die Hash-Werte überein, kann davon ausgegangen werden, dass die Daten unverändert sind. Eine Änderung an den Daten würde zu einem unterschiedlichen Hash-Wert führen, was auf eine mögliche Manipulation hinweist.

Als Beispiel sind hier SHA256 oder auch MD5 als Hash-Algorithmus zu nennen. 

#### Aufgabe 2

Eine Checksumme ist eine Zahl oder eine Zeichenfolge, die aus den Daten berechnet wird, um Fehler oder Veränderungen während der Übertragung oder Speicherung zu erkennen. Die Berechnung der Checksumme erfolgt durch Anwendung eines speziellen Algorithmus auf die Daten. Diese Checksumme wird zusammen mit den Daten übertragen.

Um die Integrität von Daten mithilfe von Checksummen zu überprüfen, berechnet der Empfänger eine neue Checksumme der empfangenen Daten und vergleicht sie mit der ursprünglichen Checksumme. Wenn die beiden Checksummen übereinstimmen, wird angenommen, dass die Daten unverändert sind. Eine Veränderung an den Daten würde zu einer unterschiedlichen Checksumme führen, was auf mögliche Fehler oder Manipulationen hinweist.

Bspw. ist hier CRC-32 (cyclic redundancy check) als Methode zu nennen.

#### Aufgabe 3

Eine Digitale Signatur ist ein kryptografisches Verfahren, bei dem der Sender einer Nachricht oder Daten einen eindeutigen digitalen Code, die Signatur, mithilfe seines privaten Schlüssels erstellt. Der Empfänger kann dann die Signatur mit dem öffentlichen Schlüssel des Senders überprüfen.

Die Integrität von Daten wird durch digitale Signaturen auf folgende Weise sichergestellt: Der Sender erzeugt einen Hash-Wert der Daten und signiert diesen mit seinem privaten Schlüssel. Der Empfänger kann dann den Hash-Wert mithilfe des öffentlichen Schlüssels des Senders entschlüsseln und mit einem selbst berechneten Hash-Wert der empfangenen Daten vergleichen. Stimmen die Hash-Werte überein und die Signatur kann erfolgreich verifiziert werden, zeigt dies an, dass die Daten unverändert und authentisch sind. Eine Änderung an den Daten oder eine ungültige Signatur würde den Prüfprozess scheitern lassen, was auf mögliche Manipulationen hinweist.

Ein Beispiel wären DocuSign oder Adobe PDF Digital Signature zu nennen.

## Vertraulichkeit herstellen

### Arbeitsauftrag - Verschlüsselung von Daten durchführen

#### Aufgabe 1

1. **Schlüsselgenerierung:**
   - Sender und Empfänger müssen denselben geheimen Schlüssel teilen.

2. **Verschlüsselung:**
   - Der Sender verwendet den gemeinsamen Schlüssel, um die Mitteilung zu verschlüsseln. Dies erzeugt den verschlüsselten Text.

3. **Übertragung:**
   - Der verschlüsselte Text wird über das unsichere Netzwerk übertragen.

4. **Empfang:**
   - Der Empfänger verwendet den gemeinsamen Schlüssel, um die Mitteilung zu entschlüsseln und den ursprünglichen Text wiederherzustellen.

#### Aufgabe 2

1. **Schlüsselgenerierung:**
   - Der Empfänger erstellt ein Schlüsselpaar mit einem öffentlichen und einem privaten Schlüssel. Der öffentliche Schlüssel wird veröffentlicht, während der private Schlüssel geheim bleibt.

2. **Verschlüsselung:**
   - Der Sender verwendet den öffentlichen Schlüssel des Empfängers, um die Mitteilung zu verschlüsseln.

3. **Übertragung:**
   - Der verschlüsselte Text wird über das unsichere Netzwerk übertragen.

4. **Entschlüsselung:**
   - Nur der Empfänger kann die Mitteilung mit seinem privaten Schlüssel entschlüsseln.

#### Aufgabe 3

Bei einer Ende-zu-Ende-Verschlüsselung werden Daten so verschlüsselt, dass nur der beabsichtigte Empfänger in der Lage ist, sie zu entschlüsseln. Dies erfolgt, unabhängig von der Anzahl der Server oder Übertragungspunkte auf dem Übertragungsweg. Selbst der Serviceanbieter, der die Daten übermittelt, kann die verschlüsselten Daten nicht lesen. Ein Beispiel hierfür ist die Ende-zu-Ende-Verschlüsselung in Messaging-Apps wie WhatsApp oder Signal.

#### Aufgabe 4

Eine Public Key Infrastructure ist eine Infrastruktur, die die Erzeugung, Verwaltung und Verteilung von Schlüsselpaaren in der asymmetrischen Verschlüsselung unterstützt. Eine PKI umfasst Zertifizierungsstellen (CAs), die digitale Zertifikate ausstellen, die die Echtheit von öffentlichen Schlüsseln bestätigen. Diese Zertifikate werden verwendet, um das Vertrauen in die asymmetrische Verschlüsselung zu stärken.

#### Aufgabe 5

Verschlüsselung und Virtual Private Networks (VPNs) sind eng miteinander verbunden. VPNs verwenden Verschlüsselungstechniken, um den Datenverkehr zwischen einem Benutzer und einem entfernten Server zu schützen. Durch die Verschlüsselung werden die Daten während der Übertragung über unsichere Netzwerke geschützt, wodurch die Privatsphäre und Sicherheit der Benutzer verbessert werden.

#### Aufgabe 6

Zero-Knowledge-Proof ist ein Beweisverfahren, bei dem eine Partei nachweisen kann, dass sie eine Information kennt, ohne die Information selbst preiszugeben. Das bedeutet, dass eine Partei in der Lage ist, etwas zu beweisen, ohne genaue Details oder den tatsächlichen Inhalt preiszugeben. Dieses Konzept wird in der Kryptografie verwendet, um Authentifizierung oder Besitz ohne Offenlegung sensibler Informationen zu ermöglichen.

### Arbeitsauftrag - Benutzer und Rollen systematisch planen

#### Aufgabe 1

Ein Verzeichnisdienst ist eine zentrale Datenbank, die Informationen über Ressourcen in einem Netzwerk speichert und verwaltet. Er spielt eine Schlüsselrolle bei der Organisation, Suche und Bereitstellung von Informationen über Benutzer, Gruppen, Computer und andere Netzwerkressourcen.

#### Aufgabe 2

- **Zentralisierter Verzeichnisdienst:** Hier werden alle Informationen an einem zentralen Ort gespeichert und verwaltet. Vorteile sind zentrale Kontrolle und einfache Verwaltung, aber Nachteile könnten Single Points of Failure und Skalierbarkeitsprobleme sein.
- **Dezentralisierter Verzeichnisdienst:** Informationen sind auf mehrere Standorte verteilt. Vorteile sind höhere Ausfallsicherheit und Skalierbarkeit, aber die Verwaltung kann komplexer sein.

#### Aufgabe 3

- Authentifizierung und Autorisierung sind entscheidend.
- Verschlüsselung für Datenübertragung.
- Überwachung von Zugriffen und Aktivitäten.
- Regelmäßige Aktualisierung von Passwörtern und Zugriffsrechten.
- Implementierung von Firewalls und Intrusion Detection Systems.

#### Aufgabe 4

**Rollen im Active Directory:**

- **Domain Controller:**
   - Ein Domain Controller (DC) ist ein Server, der das Active Directory speichert und verwaltet.
   - Er spielt eine Schlüsselrolle bei der Authentifizierung und Autorisierung von Benutzern und Ressourcen in einer Domäne.
- **Flexible Single Master Operations (FSMO) Rollen:**
   - Es gibt fünf verschiedene FSMO-Rollen im Active Directory, die bestimmte Aufgaben wie die Verwaltung von Kennwörtern und die Wartung der Verzeichnisreplikation übernehmen.
   - Dazu gehören Rollen wie der Schema-Master, Domain Naming Master, RID Master, PDC Emulator und Infrastructure Master.
- **Organizational Units (OU):**
   - OUs sind Container in einer Domäne, die dazu dienen, Objekte wie Benutzer, Gruppen und Computer zu organisieren.
   - Sie ermöglichen eine logische Strukturierung des Verzeichnisses und erleichtern die Delegation von Verwaltungsaufgaben.

**Benutzer im Active Directory:**

- **Benutzerkonten:**
   - Benutzerkonten repräsentieren individuelle Benutzer in der Active Directory-Domäne.
   - Sie enthalten Informationen wie Benutzername, Kennwort, E-Mail-Adresse und andere Attribute.
- **Gruppen:**
   - Gruppen sind Sammlungen von Benutzern, die gemeinsame Berechtigungen oder Richtlinien erhalten können.
   - Es gibt Sicherheitsgruppen und Verteilergruppen, die jeweils unterschiedliche Funktionen erfüllen.
- **Benutzerprofile:**
   - Benutzerprofile speichern individuelle Einstellungen und Anpassungen für Benutzer, wenn sie sich an einem beliebigen Computer in der Domäne anmelden.
   - Profile können lokal oder zentral (roaming) gespeichert werden.
- **Richtlinien und Berechtigungen:**
   - Das Active Directory ermöglicht die Definition von Gruppenrichtlinien, die das Verhalten von Benutzerkonten und Computern in der Domäne steuern.
   - Berechtigungen können auf Objekte in der Domäne angewendet werden, um den Zugriff zu regeln.

**Delegation von Verwaltung:**

- Die Delegation von Verwaltung ermöglicht es, bestimmte administrative Aufgaben an Benutzer oder Gruppen zu übertragen, ohne ihnen volle Kontrolle über das gesamte Verzeichnis zu geben.
- Dies erleichtert die Verteilung von Verantwortlichkeiten und die effiziente Verwaltung.