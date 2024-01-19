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