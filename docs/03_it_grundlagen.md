# IT-Grundlagen

## RAID-Level unterscheiden

### Arbeitsauftrag - RAID-Level unterscheiden

#### Aufgabe 1

Beschreiben Sie die Funktionsprinzipien des RAID 0, 1, 5, 6 sowie 10 in tabellarischer Form. Berücksichtigen Sie:

- Mindestanzahl der Festplatten
- Funktionsweise
- Nettospeicherkapazität (allgemein und am Beispiel, wenn 4x 8TB-Festplatten zur Verfügung stehen)
- Festplattenausfall (allgemein und am Beispiel
- Erweiterung des RAID-Verbunds (Anzahl Festplatten)

#### Aufgabe 2

Ein Kunde kommt auf Sie zu und möchte eine Empfehlung für ein RAID-Level auf seinem NAS. Es soll bei Ausfall von mindestens 2 Festplatten keine Probleme der Verfügbarkeit geben. Das NAS hat insgesamt 8 Laufwerke. Wenn möglich soll eine Hot Spare Festplatte eingeplant werden. Es müssen mindestens 3 der Laufwerke als Nettokapazität übrig bleiben. Welche RAID-Level ziehen Sie in Betracht? Zu welchem RAID-Level würden Sie raten, begründen Sie dieses und auch, warum andere Alternativen aus Ihrer Sicht ausscheiden.

#### Aufgabe 3

Begründen Sie in eigenen Worten, warum RAID und Backups sich für das Schutzziel der Verfügbarkeit ergänzen und nicht ersetzen.

#### Aufgabe 4

Im Rahmen der Festplattenüberwachung gibt es den S.M.A.R.T.-Standard. Was steckt hinter der Abkürzung? Beschreiben Sie außerdem kurz, was diese Prüfung ist.

#### Aufgabe 5

Was bedeutet die MTBF (Meantime Between Failure) bei Speichermedien?

## Übertragung von Daten berechnen

### Arbeitsauftrag - Übertragung von Daten berechnen

#### Aufgabe 1

Ein 3D-Drucker in einem industriellen Umfeld soll ein 3D-Modell mit einer Dateigröße von 300 MiB drucken. Die Übertragung erfolgt über eine LAN-Verbindung. Berechnen Sie die Übertragungsgeschwindigkeit in MBit/s, wenn die Übertragung 5 Minuten dauern soll.

#### Aufgabe 2

Ein 3D-Drucker in einem Industrieunternehmen benötigt, um ein druckbereites 3D-Modell zu erhalten, eine CAD-Datei, die 1,5 GiB groß ist. Die Übertragung dieser Datei erfolgt drahtlos über eine schnelle Wi-Fi-Verbindung mit einer Geschwindigkeit von 300 MBit/s. Wie lange dauert es, bis die Datei vollständig übertragen ist? Geben Sie das Ergebnis gerundet auf ganze Sekunden an.

#### Aufgabe 3

Ein großer 3D-Drucker in einem industriellen Produktionsbetrieb druckt den Prototyp eines Produkts. Während des Druckvorgangs sendet der Computer des Druckers Daten an den Drucker. Der Ingenieur geht davon aus, dass die Druckdaten eine Größe von 4,5 TiB haben sollten. Berechnen Sie die reale Gesamtmenge an Daten, die während des gesamten Druckvorgangs an den 3D-Drucker übertragen werden, wenn der Druck 8 Stunden dauert und die Übertragungsgeschwindigkeit konstant bei 50 MBit/s liegt. Geben Sie die Dateigröße in TiB an.

## Energieeffizienz von IT-Systemen vergleichen

### Arbeitsauftrag - Energieeffizienz von IT-Systemen vergleichen

#### Aufgabe 1

Für die Berechnung der Energieeffizienz bzw. der Energiekosten eines IT-Systems werden Formeln benötigt:

- Welche Formel wird herangezogen, um die elektrische Leistung P zu berechnen?
- Welche Formel wird herangezogen, um die elektrische Energie E zu berechnen?
- Welche Formel wird herangezogen, um die Kosten des Energieverbrauchs zu berechnen?

#### Aufgabe 2

Berechnen Sie die monatlichen Kosten des Energieverbrauchs für den Betrieb eines Einplatinencomputers, wie dem Raspberry Pi. Dieser hat einen Stromverbrauch im Normalbetrieb von 1750 mA, unter Verwendung des 5V Netzteils. Die Betriebsdauer liegt bei 12 Stunden pro Tag für 30 Tage je Monat. Der Strompreis liegt bei 35 ct/kWh.

#### Aufgabe 3

Sie haben die Aufgabe, für ein Projekt bei einem Kunden mit zwei Lösungsvorschlägen für den Einsatz von IT-Systemen, die Energiekosten zu berechnen und zu vergleichen.

Es handelt sich dabei um 40 Arbeitsplätze, die ausgestattet werden sollen. Ein Arbeitsplatz wird 250 Tage im Jahr für 10 Stunden je Tag betrieben. Server können nicht heruntergefahren werden, sodass diese 24/7 für 365 Tage im Jahr durchgehend laufen. Der Strompreis liegt bei 31 ct/kWh.
 
- Option A: Für jeden Arbeitsplatz einen Mini-Desktop-PCs (ZBOX PI336 pico) mit 15 Watt im normalen Anwendungsbetrieb sowie einem Server (HPE ProLiant DL360 Gen10) für verschiedene Anwendungen mit 800 Watt Netzteil. Der Server hat eine Energieauslastung von 95%.
- Option B: ThinClients (Dell OptiPlex 3000) mit 40 Watt im normalen Anwendungsbetrieb sowie zwei Server (HPE ProLiant DL360 Gen10) für die Virtual Desktop Interfaces (VDI) mit jeweils 800 Watt Netzteilen. Die Server haben eine Energieauslastung von 85%.

Berechnen Sie die Gesamtkosten für beide Optionen je Kalenderjahr und benennen Sie die günstigere Lösung.

#### Aufgabe 4

Lesen Sie sich den folgenden englischsprachigen Beitrag zum Thema "Power Usage Effectiveness (PUE) durch und beantworten Sie die Fragen hierzu auf deutsch:

**What is Power Usage Effectiveness (PUE)?**

Power Usage Effectiveness (PUE) is a metric that can be used to estimate the energy efficiency of a data center. It is calculated by dividing the total amount of energy entering a data center by the energy required only to operate the IT equipment in the data center. The closer this value approaches 1.0, the more efficient the data center.

Monitoring a metric like PUE is useful for benchmarking data center efficiency. Companies and data center managers use the metric to determine the current efficiency of their infrastructure and the success of modernization efforts. This helps reduce power consumption and energy costs.

PUE was developed by members of the Green Grid, an industry group focused on data center energy efficiency. According to the Uptime Institute Annual Global Data Center Survey 2021, PUE and power consumption are among the best tracked metrics for improving sustainability. A similar benchmarking standard recognized by the Green Grid is Data Center Infrastructure Efficiency (DCiE).

**How to calculate the PUE?**

PUE is calculated by dividing the total facility power consumption by the power consumption of the IT equipment. Total facility power is the amount of energy consumed by the facility, which includes all data center hardware, power supply components, air conditioning systems, and lighting. IT equipment energy refers to the amount of energy used to power storage, compute, networking, and input/output devices (such as monitors).

**Advantages of and criticism of PUE**

Applying PUE to determine facility energy efficiency and environmental performance has some advantages:

- You can recalculate it as often as you like. The metric is designed to be recalculated on an ongoing basis to assess the effectiveness of countermeasures.
- More efficient practices are reflected in the PUE. The metric helps identify effective and non-effective ways to reduce energy consumption.
- The value is a popular metric in DCIM software. DCIM software usually calculates PUE in real time and reports on it.
- The PUE metric is useful in a competitive environment. Companies with good PUE metrics should include them in their promotional materials.

However, the PUE metric for data centers is subject to some limitations, for example:

- It is difficult to accurately calculate the total power. However, this is an important factor that significantly influences the informative value of the PUE. If you have to estimate this number at your electricity meter, then even PUE is only a rough estimate.
- PUE does not capture consumption at the rack level. Energy used for rack-level infrastructure is not included in the overall PUE calculation, making PUE less accurate.
- PUE is not actually a marketing metric. Although companies can use the PUE metric for marketing purposes, it is intended as an improvement and evaluation metric. Marketers should not rely too heavily on PUE just because it is a widely known concept.
- PUE says nothing about whether the data center is reasonably sized and whether you are using efficient software. It's still possible to waste power with a low PUE if you're not using your IT resources wisely.
- PUE does not capture other environmental factors, such as water absorption, asset useful life, or the rate of recycling of retired assets. It is possible to lower PUE by making environmentally unfriendly, premature new purchases, but do more harm to the environment on balance.

**How can you lower the PUE value?**

To bring your PUE closer to 1.0, the following measures are possible:

- Virtualize servers. Virtualization enables you to run the same workloads on fewer servers. This gives you more computing power with the same or smaller infrastructure.
- Optimize cooling. Air conditioning systems are among the most energy-intensive components of data center infrastructure. Depending on how you plan your layout, you can avoid hotspots and thus the need for additional cooling power.
- Use free cooling. Because air-conditioning systems are so power-hungry, rely on outside air cooling as often as possible, which uses much less power.
- Retire inefficient hardware. First, the efficiency of hardware deteriorates as it ages, and second, new hardware on the market is becoming more efficient. But before you decide to upgrade, you should calculate whether the energy savings are worth the CO2 emissions of manufacturing a new device. In most cases, the equipment you already own is the most environmentally friendly.
- Deploy a more efficient UPS. UPSs are essential to maintain operations throughout. But there are more or less efficient options here.
- Don't forget lighting. While the energy used for lighting is only a small part of the data center's power needs, it's especially easy to reduce that portion. Make sure lights are only on when employees really need them (for example, through a motion detector or timer) and switch light sources to LEDs.

*Quelle: Fontecchio, Mark & Gillis, Alexander S. (2023). Power Usage Effectiveness (PUE). URL: https://www.computerweekly.com/de/definition/Power-Usage-Effectiveness-PUE.*

**Fragen:**

1. Was ist Power Usage Effectiveness (PUE) und wie wird diese berechnet?
2. Warum ist es wichtig, die Energieeffizienz eines Rechenzentrums zu messen?
3. Welche Vorteile bietet die Anwendung des PUE-Metriks für Rechenzentren?
4. Welche Kritikpunkte gibt es in Bezug auf den PUE-Wert?
5. Wie kann man den PUE-Wert senken und die Energieeffizienz steigern?
6. Welche Rolle spielt die Virtualisierung bei der Verbesserung des PUE-Werts?
7. Warum ist die Optimierung der Kühlung in einem Rechenzentrum wichtig?
8. Was versteht man unter "free cooling" und wie trägt es zur Senkung des PUE bei?
9. Warum ist die Wahl eines effizienten USV-Systems für die Energieeffizienz entscheidend?
10. Welche Maßnahmen können ergriffen werden, um den Energieverbrauch für Beleuchtung in einem Rechenzentrum zu reduzieren?

## Ergonomie am Arbeitsplatz herstellen

### Arbeitsauftrag - Ergonomie am Arbeitsplatz herstellen

#### Aufgabe 1

#### Aufgabe 2

#### Aufgabe 3

#### Aufgabe 4

## Cloudlösungen unterscheiden

### Arbeitsauftrag - Cloudlösungen unterscheiden

#### Aufgabe 1

#### Aufgabe 2

#### Aufgabe 3

#### Aufgabe 4

## Hardwarekomponenten unterscheiden

### Arbeitsauftrag - Hardwarekomponenten unterscheiden

#### Aufgabe 1

#### Aufgabe 2

#### Aufgabe 3

#### Aufgabe 4

## Virtualisierung nutzen

### Arbeitsauftrag - Virtualisierung nutzen

#### Aufgabe 1

#### Aufgabe 2

#### Aufgabe 3

#### Aufgabe 4

{%
   include-markdown "inhalte/lizenzhinweis.md"
   start="<!--include-start-->"
   end="<!--include-end-->"
%}