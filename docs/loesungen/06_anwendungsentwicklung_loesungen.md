# Anwendungsentwicklung

## UML-Anwendungsfalldiagramme erstellen

### Arbeitsauftrag - UML-Anwendungsfalldiagramme erstellen

#### Aufgabe 1

Das UML-Anwendungsfalldiagramm ist in der objektorientierten Programmierung (OOP) ein wichtiges Werkzeug zur Modellierung und Visualisierung der funktionalen Anforderungen eines Systems. Es dient dazu, die verschiedenen Funktionen oder Aufgaben (Anwendungsfälle) zu identifizieren, die ein System für seine Benutzer oder externe Systeme bereitstellen soll.

1. **Identifikation von Anwendungsfällen:** Das Anwendungsfalldiagramm hilft dabei, die verschiedenen Aktivitäten oder Aufgaben zu identifizieren, die ein System für Benutzer oder externe Systeme ausführt.
2. **Darstellung von Benutzerinteraktionen:** Es visualisiert die Interaktionen zwischen den Benutzern (Akteuren) und dem System. Das zeigt, wie die Benutzer mit dem System agieren und welche Funktionen sie ausführen können.
3. **Definition von Systemgrenzen:** Das Diagramm hilft dabei, klare Grenzen für das System zu setzen, indem es zeigt, wer die Hauptakteure sind und welche Aufgaben innerhalb des Systems durchgeführt werden.
4. **Festlegung von Systemfunktionen:** Es unterstützt die Festlegung und Dokumentation der Funktionen, die das System für seine Benutzer bereitstellt. Dies erleichtert die Kommunikation zwischen Stakeholdern, Entwicklern und anderen Beteiligten.
5. **Basis für Systementwicklung:** Das Anwendungsfalldiagramm dient als Grundlage für die weitere Systementwicklung in der OOP. Es unterstützt die Definition von Klassen, Methoden und anderen relevanten Systemkomponenten.
6. **Schnittstellenidentifikation:** Es hilft bei der Identifikation von Schnittstellen zwischen dem System und seinen Benutzern oder anderen Systemen.
7. **Testfallableitung:** Es unterstützt die Ableitung von Testfällen, indem es klare Szenarien für die Nutzung des Systems definiert. Dies erleichtert die Überprüfung, ob das System die definierten Anforderungen erfüllt.

#### Aufgabe 2

- **Akteur:** Ein Akteur repräsentiert eine externe Entität, die mit dem System interagiert. Dies können Personen, Gruppen von Personen, andere Systeme oder sogar Hardware sein. Akteure werden durch Piktogramme in der Form von Kästen dargestellt, normalerweise oben auf dem Diagramm platziert.
- **Systemgrenze:** Die Systemgrenze definiert den Umfang des Systems und zeigt an, welche Elemente als Teil des Systems betrachtet werden. Die Systemgrenze wird durch eine Linie um das gesamte Diagramm dargestellt und gibt an, welche Akteure und Anwendungsfälle innerhalb des Systems modelliert werden.
- **Anwendungsfall:** Ein Anwendungsfall repräsentiert eine spezifische Funktion oder Aufgabe, die das System für einen oder mehrere Akteure durchführt. Ein Anwendungsfall wird durch einen Ellipsen-förmigen Kasten dargestellt und normalerweise mit einem Namen beschriftet.
- **Beziehung:** Beziehungen verbinden Akteure und Anwendungsfälle miteinander. Sie zeigen an, wie die Akteure mit den Anwendungsfällen interagieren. Es gibt zwei Hauptarten von Beziehungen: include und extend.
  - **include-Beziehung:** Die include-Beziehung zeigt an, dass ein Anwendungsfall einen anderen Anwendungsfall einschließt. Dies bedeutet, dass der eingeschlossene Anwendungsfall unabhängig vom umfassenden Anwendungsfall existieren und ausgeführt werden kann. Die include-Beziehung wird durch eine gestrichelte Linie mit einem offenen Pfeil dargestellt, der auf den eingeschlossenen Anwendungsfall zeigt.
  - **extend-Beziehung:** Die extend-Beziehung zeigt an, dass ein Anwendungsfall optional erweitert werden kann. Der erweiternde Anwendungsfall wird nur unter bestimmten Bedingungen oder Szenarien ausgeführt. Die extend-Beziehung wird durch eine gestrichelte Linie mit einem offenen Pfeil dargestellt, der vom erweiternden Anwendungsfall zum erweiterten Anwendungsfall zeigt.

#### Aufgabe 3

!!!info "User Stories"
  User Stories sind eine Methode in der agilen Softwareentwicklung, um Anforderungen aus der Perspektive des Benutzers zu formulieren. Sie sind kurz, prägnant und fokussieren sich darauf, welchen Nutzen der Benutzer aus einer bestimmten Funktionalität zieht. Eine typische User Story folgt dem Format:
  
  "Als [Rolle] möchte ich [Funktionalität], um [Nutzen/Ziel]."

- Als Benutzer möchte ich den Druckfortschritt überwachen, um die Auslastung des Druckers zu optimieren.
- Als Benutzer möchte ich den Druck abbrechen, um bei Fehlerfällen schnell reagieren zu können.
- Als Benutzer möchte ich ein 3D-Modell auswählen, um dieses drucken zu können.
- Als Benutzer möchte ich den Druckauftrag starten, um die Produktion eines Bauteils zu beginnen.
- Als Wartungspersonal möchte ich die Wartung durchführen, um ohne Unterbrechungen am Drucker Einstellungen vorzunehmen.
- Als Wartungspersonal möchte ich die Druckparameter einstellen, um ein möglichst optimales Produktionsergebnis zu erhalten.

#### Aufgabe 4



## UML-Klassendiagramme erstellen

### Arbeitsauftrag - UML-Klassendiagramme erstellen

## Struktogramme zur Planung von Anwendungen nutzen

### Arbeitsauftrag - Struktogramme erstellen

#### Aufgabe 1

- **Anweisungen:**
  - Eingabe: Hier werden Daten eingegeben, sei es durch den Benutzer oder durch andere Teile des Programms.
  - Ausgabe: Hier erfolgt die Ausgabe von Daten in der Kommandozeile.
  - Standardanweisung: Eine einzelne Operation oder Aktion.
- **Schleifen:**
  - Zählergesteuerte Schleife: Sie wird verwendet, wenn die Anzahl der Schleifendurchläufe im Voraus bekannt ist.
  - Kopfgesteuerte Schleife: Eine Schleife, bei der die Bedingung am Anfang überprüft wird.
  - Fußgesteuerte Schleife: Die Bedingung wird am Ende der Schleife überprüft.
- **Kontrollstrukturen:**
  - Verzweigung: Je nach Bedingung wird der Programmfluss in zwei verschiedene Richtungen (Wahr oder Falsch) verzweigt.
  - Fallunterscheidung: Ähnlich wie Verzweigung, jedoch mit mehreren Bedingungen und verschiedenen Pfaden.
  - Try-Catch: Wird verwendet, um Ausnahmen oder Fehler zu behandeln. Der "Try"-Block enthält den auszuführenden Code, während der "Catch"-Block aufgerufen wird, wenn eine Ausnahme auftritt.
- **Funktionen:**
  - Sie repräsentieren einen separaten Abschnitt des Codes, der eine bestimmte Aufgabe erfüllt. Funktionen können Parameter enthalten, die als Eingabe dienen (sogeannte Übergabeparameter), und können Werte zurückgeben.

#### Aufgabe 2

**Ziel der Verwendung von Struktogrammen:**

Das Hauptziel der Verwendung von Struktogrammen liegt in der klaren und verständlichen Planung von Programmlogiken. Struktogramme bieten eine grafische Darstellung von Algorithmen und Programmen, die es ermöglicht, den Ablauf und die Struktur des Codes visuell zu erfassen. Durch die Verwendung dieser Notationsform soll die Entwicklung von Software effizienter und fehlerärmer gestaltet werden. Die wichtigsten Ziele sind:

1. **Klare Darstellung:** Struktogramme bieten eine klare und gut strukturierte Darstellung der Programmlogik, wodurch Entwickler leicht verstehen können, wie der Code funktionieren soll.
2. **Logische Strukturierung:** Die grafische Notation hilft dabei, die logische Struktur des Codes zu visualisieren, einschließlich Verzweigungen, Schleifen und Funktionen. Dies erleichtert die Planung und Organisation des Codes.
3. **Fehlervermeidung:** Durch die frühzeitige Visualisierung des Algorithmus können potenzielle Fehler oder Inkonsistenzen leichter erkannt und behoben werden, bevor der eigentliche Programmcode geschrieben wird.
4. **Kommunikation:** Struktogramme dienen als effektives Kommunikationsmittel zwischen Entwicklern, indem sie eine gemeinsame visuelle Sprache bieten. Teammitglieder können die Logik leichter besprechen und verstehen.

**Vor- und Nachteile von Struktogrammen:**

**Vorteile:**

1. **Klarheit und Verständlichkeit:** Die grafische Darstellung erleichtert das Verständnis der Programmlogik, sowohl für den Entwickler, der den Code erstellt, als auch für andere Teammitglieder.
2. **Fehlererkennung:** Durch die visuelle Darstellung können Fehler und Unstimmigkeiten in der Logik frühzeitig erkannt und behoben werden, was zur Verbesserung der Codequalität beiträgt.
3. **Planungshilfe:** Struktogramme dienen als nützliche Werkzeuge in der Planungsphase, indem sie Entwicklern helfen, den Algorithmus zu entwerfen, bevor der eigentliche Code geschrieben wird.
4. **Effektive Kommunikation:** Sie bieten eine gemeinsame Notation, die die Kommunikation zwischen Teammitgliedern erleichtert und Missverständnisse reduziert.

**Nachteile:**

1. **Begrenzte Detailtiefe:** Struktogramme können in komplexen Programmen manchmal an Detailtiefe verlieren, insbesondere wenn es um komplexe Datenstrukturen oder spezifische Implementierungsdetails geht.
2. **Nicht immer maschinenlesbar:** Struktogramme sind primär für den menschlichen Leser gedacht und werden nicht direkt von Computern interpretiert. Der eigentliche Programmcode muss separat geschrieben werden.
3. **Zeitaufwändig:** Das Erstellen detaillierter Struktogramme kann zeitaufwändig sein, insbesondere für umfangreiche Programme. In einigen Fällen kann dies als zusätzlicher Schritt wahrgenommen werden.
4. **Abstraktion:** Manchmal kann die Abstraktion in Struktogrammen zu einer gewissen Entfremdung von konkreten Code-Implementierungen führen, was für einige Entwickler eine Herausforderung darstellen könnte.

#### Aufgabe 3

![Struktogramm](../bilder/06_struktog_aufgabe_3_python.png)

#### Aufgabe 4

![Struktogramm](../bilder/06_struktog_aufgabe_4_powershell.png)

#### Aufgabe 5

![Struktogramm](../bilder/06_struktog_aufgabe_5_bücherei.png)
