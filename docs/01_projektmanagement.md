# Projektmanagement (div. LF)

![Kapitelbild](bilder/kap_01_kapitelbild.jpg)

- Projekte definieren
- Netzplantechnik anwenden
- Gantt-Diagramme anwenden
- Anforderungen erheben
- Lasten- und Pflichtenheft unterscheiden

---

## Projekte definieren

### Arbeitsauftrag - Projekte definieren

#### Aufgabe 1

Definieren Sie, was ein Projekt ist und anhand welcher Kriterien festgestellt werden kann, ob ein Vorgang ein Projekt oder doch Tagesgeschäft ist.

#### Aufgabe 2

Beschreiben Sie in eigenen Worten, was hinter der Projektmanagementmethode PRINCE2 steht.

#### Aufgabe 3

Nennen Sie die Phasen eines Projektes in der korrekten Reihenfolge und ordnen Sie diesen jeweils ein Dokument / Artefakt zu, welches für die Phase typisch ist.

#### Aufgabe 4

Welche Stakeholder hat ein Projekt in einem Unternehmen?

---

## Netzplantechnik anwenden

Für die IHK-Prüfung sollten Sie den Netzplan am besten mit Stift und Papier üben. Für die Anwendung in Projekten ist eine softwarebasierte Nutzung ggf. sinnvoll. Hierfür wäre bspw. draw.io (auch wenn es darin den Typ "Netzplan" nicht direkt gibt) möglich.

### Draw.io

- Hier geht es zur [Webversion von draw.io.](https://draw.io)
- Für Visual Studio Code gibt es auf [dieser offziellen Webseite ein draw.io-Plugin](https://marketplace.visualstudio.com/items?itemName=hediet.vscode-drawio).

### Vorlage eines Netzplans für draw.io

- Die Vorlage können Sie sich hier herunterladen: [Download](material/01_vorlage_npt.drawio)
- Anschließend öffnen Sie diese im draw.io-Editor.

### Arbeitsauftrag - Netzpläne erstellen

Eine neue Filiale eines Optikers soll mit Hardware ausgestattet werden. Der Filialleiter möchte hiervon von der IT-Abteilung des Konzerns eine zeitliche Übersicht erhalten. Nachdem Sie bei den entsprechenden Kolleginnen nachgefragt haben, erhalten Sie folgende tabellarische Übersicht:

| Vorgang | Vorgangsbezeichnung | Dauer in Tagen | Nachfolger |
| :--- | :--- | :---: | :---: |
| A | Auswahl der Hardware | 1 | B,C,D |
| B | Beschaffung der Notebooks | 7 | E |
| C | Beschaffung der Netzwerkkomponenten | 10 | F |
| D | Beschaffung der Server | 6 | G |
| E | Konfiguration der Notebooks | 2 | H |
| F | Konfiguration der Netzwerkkomponenten | 3 | H |
| G | Konfiguration der Server | 1 | H |
| H | Installation | 2 | I |
| I | Funktionstest | 1 | J |
| J | Einweisung | 1 | - |

#### Aufgabe 1

Erstellen Sie einen Netzplan zur grafischen Visualisierung des Zeitablaufs. Berücksichtigen Sie dabei sowohl die Darstellung des freien Puffers, als auch des Gesamtpuffers.

#### Aufgabe 2

Wie verläuft der kritische Pfad?

#### Aufgabe 3

Wie unterscheiden sich der freie Puffer und der Gesamtpuffer?

#### Aufgabe 4

Angenommen der Lieferant kann die Server erst 8 Tage später liefern, welche Auswirkungen hat dies auf die geplante Projektdauer?

#### Aufgabe 5

Was kann der Projektleiter unternehmen, um trotz einer relevanten Verschiebung des Projektfinales nach hinten, das ursprüngliche Projektende zu erreichen?

---

## Gantt-Diagramme anwenden

### Arbeitsauftrag Gantt-Diagramme erstellen

In einem Café soll eine bestehende Anwendung zur Verwaltung von Mitarbeiterstammdaten und Tischreservierungen des Betriebs um ein Modul zur Arbeitszeiterfassung der Servicekräfte ergänzt werden. Dazu wurde folgende Zeitplanung erstellt:

| Vorgang | Vorgangsbezeichnung | Dauer in Tagen | Vorgänger | Nachfolger |
| :---: | :--- | :---: | :---: | :---: |
| A | Datenbankmodell entwickeln | 7 | - | B,C,D |
| B | Datenbanktabellen implementieren | 2 | A | E |
| C | Abfragen entwickeln | 4 | A | E |
| D | Formulare und Berichte erstellen | 8 | A | F |
| E | Abfragen testen | 3 | B,C | F |
| F | Anwendung testen | 5 | D,E | G |
| G | Benutzerhandbuch erstellen | 5 | F | H |
| H | Installation und Inbetriebnahme | 2 | G | - |

#### Aufgabe 1

Erstellen Sie ein Gantt-Diagramm, wenn das Projekt am 03.03.2025 startet. An Samstagen, Sonntagen und Feiertagen wird nicht an dem Projekt gearbeitet.

#### Aufgabe 2

Wie verläuft der kritische Pfad?

#### Aufgabe 3

Welche Vorteile hat das Gantt-Diagramm gegenüber dem Netzplan?

#### Aufgabe 4

Welche Nachteile hat das Gantt-Diagramm gegenüber dem Netzplan?

---

**Informationsmaterial zu dieser Kompetenz:**

### Lernvideo - Gantt-Diagramm (Studyflix)

[Studyflix - Gantt-Diagramm](https://studyflix.de/wirtschaft/gantt-diagramm-659)

---

## Anforderungen erheben

### Arbeitsauftrag - Anforderungen erheben

#### Aufgabe 1

Beschreiben Sie in eigenen Worten den Unterschied zwischen funktionalen und nicht-funktionalen Anforderungen.

#### Aufgabe 2

Mit welchen Methoden können Anforderungen für ein Projekt im Unternehmensumfeld generell erhoben werden?

#### Aufgabe 3

Welchen Gütekriterien sollte eine formulierte Anforderung genügen?

#### Aufgabe 4

Zur Dokumentation von Anforderungen bspw. an eine Software können sogenannte User Stories genutzt werden. Beschreiben Sie in eigenen Worten, was dies ist. Stellen Sie außerdem einen Zusammenhang zum UML Use-Case-Diagramm her.

---

**Informationsmaterial zu dieser Kompetenz:**

[Informationsmaterial - Anforderungen (IT-Berufe Podcast & Shownotes)](https://it-berufe-podcast.de/anforderungsermittlung-nicht-nur-fuer-dein-abschlussprojekt-it-berufe-podcast-159/)

---

## Lasten- und Pflichtenheft unterscheiden

### Aufgabe 1

Beschreiben Sie in eigenen Worten, was ein Lastenheft ist und wer dieses aus welcher Motivation heraus erstellt.

### Aufgabe 2

Nennen Sie übliche Inhalte eines Lastenheftes.

### Aufgabe 3

Beschreiben Sie in eigenen Worten, was ein Pflichtenheft ist und wer dieses aus welcher Motivation heraus erstellt.

### Aufgabe 4

Stellen Sie nochmals den Unterschied zwischen Lasten- und Pflichtenheft heraus.

{%
   include-markdown "inhalte/lizenzhinweis.md"
   start="<!--include-start-->"
   end="<!--include-end-->"
%}