# IT-Grundlagen

## RAID-Level unterscheiden

### Arbeitsauftrag - RAID-Level unterscheiden

#### Aufgabe 1

| Kriterium | RAID 0 | RAID 1 | RAID 5 | RAID 6 | RAID 10 |
| :--- | :--- | :--- | :--- | :--- | :--- |
| Mindestanzahl der Festplatten | 2 | 2 | 3 | 4 | 4 |
| Funktionsweise | Striping | Mirroring | Striping mit Parity | Striping mit Double-Parity | Striping mit anschließendem Mirroring |
| Nettospeicherkapazität allgemein | Kapazität der kleinsten Festplatte * Anzahl der Festplatten | Kapazität der kleinsten Festplatte | Kapazität der kleinsten Festplatte * (Anzahl der Festplatten - eine Festplatte) | Kapazität der kleinsten Festplatte * (Anzahl der Festplatten - zwei Festplatten) | Kapazität der kleinsten Festplatte * Anzahl der Festplatten / 2 |
| Nettospeicherkapazität am Beispiel | 8 TB * 4 = 32 TB | 8 TB | 8 TB * (4 - 1) = 24 TB | 8 TB * (4 - 2) = 16 TB | 8 TB * 4 / 2 = 16 TB |
| Festplattenausfall ohne Datenverlust allgemein | keine | alle bis auf eine | max. eine | max. zwei | max. die Hälfte, wenn immer nur eine aus dem jeweiligen RAID 1 Verbund betroffen ist |
| Festplattenausfall ohne Datenverlust am Beispiel | keine | max. 3 | max. 1 | max. 2 | Best-Case: max. 2 (aus unterschiedlichem RAID 1 Verbund) / Worst-Case: max. 1 (wenn sonst die zweite Festplatte eines RAID 1 Verbunds betroffen sind) |
| Erweiterung des RAID-Verbunds | immer um eine Festplatte möglich | immer um eine Festplatte möglich | immer um eine Festplatte möglich | immer um eine Festplatte möglich | immer um zwei Festplatten als weiteren RAID 1 Verbund möglich |

#### Aufgabe 2

Das NAS hat 8 Laufwerke. Ein Laufwerk davon dient als Hot Spare (nicht im Verbund befindlich und bereit für ein ausgefallenes Laufwerk an die Stelle zu treten) und damit 7 aktiven Laufwerken eine ungerade Anzahl.

In näheren Betracht kommen die RAID-Level 6 und 10, da bei beiden Konzepten zwei Laufwerke ohne Datenverlust ausfallen dürfen (bei RAID 10 und Best-Case sogar mehr).

Da das RAID-Level 10 allerdings eine gerade Anzahl Laufwerke benötigt, würde die Kapazität der 7. aktiven Festplatte nicht eingebracht werden können. Damit bleibt lediglich RAID 6 als Option übrig.

Die Mindestnettokapazität von drei Festplatten ist beim RAID 6 bei 7 aktiven Laufwerken gegeben, es werden zwei Laufwerke für Paritäten verwendet, es bleiben damit fünf Laufwerke für die Nettokapazität:

- 5 Laufwerke Nettokapazität
- 2 Laufwerke für Paritäten
- 1 Laufwerk als Hot Spare

#### Aufgabe 3

RAID und Backups sind beide wichtige Strategien zur Sicherung von Daten, insbesondere hinsichtlich des Schutzziels der Verfügbarkeit. Sie ergänzen sich jedoch, anstatt sich zu ersetzen, aus verschiedenen Gründen:

- **Fehlerhafte Datenspeicherung:** RAID-Systeme bieten Redundanz auf Hardwareebene und sind in der Lage, den Ausfall eines oder mehrerer Festplatten zu tolerieren, ohne dass Datenverlust auftritt. Dies trägt zur kontinuierlichen Verfügbarkeit bei, da der Betrieb weitergehen kann, selbst wenn Hardwarefehler auftreten. Allerdings schützt RAID nicht vor Datenverlust aufgrund von Fehlern auf Dateiebene, menschlichen Fehlern oder schädlicher Software.
- **Datenkorruption und Löschungen:** RAID schützt zwar vor physischen Festplattenausfällen, kann jedoch nicht vor Datenkorruption oder versehentlichen Löschungen schützen. In diesen Fällen sind Backups von entscheidender Bedeutung. Backups speichern Daten zu einem bestimmten Zeitpunkt und ermöglichen die Wiederherstellung von Daten, die in der Vergangenheit verloren gegangen sind.
- **Katastrophenschutz:** Backups sind unerlässlich, wenn es darum geht, Daten vor größeren Katastrophen zu schützen, wie zum Beispiel Naturkatastrophen, Brand oder Diebstahl. RAID-Systeme können den Ausfall von Festplatten in derselben physischen Umgebung bewältigen, bieten jedoch keinen Schutz, wenn die gesamte Umgebung zerstört wird. Backups, die an einem externen Ort aufbewahrt werden, stellen sicher, dass Daten selbst nach solchen katastrophalen Ereignissen wiederhergestellt werden können.
- **Historische Daten und Versionierung:** Backups ermöglichen es, auf historische Daten zuzugreifen und verschiedene Versionen von Dateien wiederherzustellen. RAID bietet in der Regel keine umfassende Versionierung. Dies ist wichtig, wenn es darum geht, frühere Datenzustände wiederherzustellen oder geänderte Dateien zu vergleichen.

#### Aufgabe 4

S.M.A.R.T. steht für "Self-Monitoring, Analysis, and Reporting Technology", was auf Deutsch etwa "Selbstüberwachung, Analyse und Berichterstattungstechnologie" bedeutet. Es handelt sich um einen branchenweiten Standard, der in Festplatten und SSD eingebaut ist. Die Hauptfunktion von S.M.A.R.T. besteht darin, die Gesundheit und Leistungsfähigkeit der Speichermedien zu überwachen und frühzeitig auf potenzielle Probleme oder drohende Ausfälle hinzuweisen.

S.M.A.R.T. sammelt eine Vielzahl von Daten und Parametern von der Festplatte, wie beispielsweise die Anzahl der fehlerhaften Sektoren, die Betriebstemperatur, die Anzahl der Betriebsstunden und vieles mehr. Diese Informationen werden von der Festplatte selbst überwacht, um Veränderungen oder Abweichungen von den erwarteten Werten zu erkennen. Wenn kritische Schwellenwerte überschritten werden oder Anomalien auftreten, kann S.M.A.R.T. Warnmeldungen generieren, um den Benutzer oder das System darauf hinzuweisen, dass eine Wartung oder ein Austausch der Festplatte erforderlich sein könnte.

Durch die regelmäßige Überwachung von S.M.A.R.T.-Daten können Benutzer und Systemadministratoren frühzeitig auf Probleme reagieren, bevor es zu einem vollständigen Ausfall der Festplatte kommt. Dies ermöglicht eine bessere Planung für die Datensicherung und den Austausch von Festplatten, um Datenverlust und Unterbrechungen zu minimieren. S.M.A.R.T. ist daher ein wichtiges Instrument zur Verbesserung der Verfügbarkeit und Zuverlässigkeit von Datenspeichergeräten.

#### Aufgabe 5

MTBF, oder "Meantime Between Failure" (deutsch: "Mittlere Betriebsdauer zwischen Ausfällen"), ist eine Kennzahl, die in der Informatik und insbesondere bei Speichermedien wie Festplatten und SSDs verwendet wird, um die erwartete durchschnittliche Zeitdauer zwischen Ausfällen oder Störungen zu quantifizieren. Die MTBF ist ein wichtiger Wert zur Bewertung der Zuverlässigkeit und Haltbarkeit von Hardwarekomponenten.

Die MTBF wird in Stunden oder Betriebszyklen gemessen und gibt an, wie lange ein Gerät im Durchschnitt zwischen zwei aufeinanderfolgenden Ausfällen oder Störungen funktionieren sollte. Je höher die MTBF ist, desto zuverlässiger wird das Speichermedium angesehen. Es ist jedoch wichtig zu beachten, dass die MTBF keine Garantie für die genaue Betriebsdauer eines einzelnen Geräts ist, sondern vielmehr eine statistische Schätzung basierend auf umfangreichen Tests und Erfahrungen mit ähnlichen Geräten.

Die MTBF ist ein nützlicher Indikator, um die Ausfallsicherheit von Speichermedien und anderen Hardwarekomponenten bei der Planung von IT-Infrastrukturen zu berücksichtigen. Organisationen können die MTBF-Werte verwenden, um Redundanz- und Backup-Strategien zu entwickeln, um sicherzustellen, dass Datenverlust und Betriebsunterbrechungen aufgrund von Hardwareausfällen minimiert werden.

## Übertragung von Daten berechnen

### Arbeitsauftrag - Übertragung von Daten berechnen

#### Aufgabe 1

![Aufgabe 1](../bilder/kap_03_uebertragung_von_daten_aufgabe_1.png)

#### Aufgabe 2

![Aufgabe 2](../bilder/kap_03_uebertragung_von_daten_aufgabe_2.png)

#### Aufgabe 3

![Aufgabe 3](../bilder/kap_03_uebertragung_von_daten_aufgabe_3.png)