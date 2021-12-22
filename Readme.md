# Zweite Übungsaufgabe: Christmas Card Generator

Entwickeln Sie eine einfache, browser-basierte Anwendung, mit der Nutzer\*innen kleine GIF-Animationen erstellen und als Weihnachtskarte verwenden können..

Die Anleitung zur Aufgabe (*Handout*) finden Sie [hier](https://multimedia-engineering.git-pages.uni-regensburg.de/mme-online/#/Aufgaben/WS2122/WS2122-ChristmasCardGenerator).

## Pairing-Sitzungen

Für die Implementierung der Aufgabe sollten Sie mindestens zwei _Pair Programming_-Sitzungen an unterschiedlichen Tagen einplanen. Legen Sie im Vorfeld fest, an welchen Teilen der Aufgabe Sie arbeiten wollen. Bereiten Sie sich jeweils konkret auf die Umsetzung dieser geplanten _Features_ vor. Natürlich können Sie auch in weiteren Sitzungen am gemeinsamen Lösungsvorschlag arbeiten. Bitte dokumentieren Sie im Anschluss an jede Sitzung kurz, an welchen Teilen der Aufgaben Sie gearbeitet haben und welche Ziele Sie in der Sitzung erreicht haben. Sie können sich dabei an diesem Beispiel orientieren.

### Sitzung 01, 1. Januar 1970, 13:37 Uhr

(Wechsel zwischen Driver und Navigator nach jeweils ca. 30 Minuten)

#### Geplant war die Bearbeitung dieser Features

- Konfigurationsmodule implementieren \[**abgeschlossen**\]
- Interaktion mit Menüs umsetzen \[**abgeschlosse**\]
- Model für Canvas entwerfen. \[**unvollstädnig**\]

**Erreichter Zustand**: Alle wichtigen Werte und Informationen werden in einem zentralen Modul verwaltet. Bei der Auswahl von Menüelementen werden die gewünschten Aktionen über eine Observer-Schnittstelle weitergeben. Die aktuell ausgewählte Farbe bzw. das aktuell ausgewählte Werkzeug werden im UI hervorgehoben.
