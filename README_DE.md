#Rezeptbuch
[![Statusübersicht-Badge](../../blob/badges/.github/badges/autograding/badge.svg)](#Ergebnisse)


## Übung I

- [x] Erstelle im Ordner `recipes` eine neue Datei mit der grundlegenden html-Struktur, mit der folgenden Namenskonvention `index.html`.
- [x] Erstelle ein Meta-Tag mit dem Namen author und deinem Namen als Wert.
- [x] Ändere den Titel der Seite in den Namen des Rezepts.

---

## Übung II

- [x] Suche und/oder lade ein Bild für dein Rezept herunter und lege es in den Ordner `img`.
- Füge das Bild deines Rezepts in die Html-Seite ein, der Fallback-Text für das Bild sollte der Name des Rezepts sein, das Bild muss 500 px breit sein

---

## Übung III

- [x] Füge unter dem Bild die Hauptüberschrift deiner Seite ein. Die Überschrift sollte der Name deines Rezepts sein.
- [x] Füge zwei weitere Überschriften zu deiner Seite hinzu. Auf der ersten sollte "Zutaten" und auf der zweiten "Zubereitung" stehen.

---

## Übung IV

- [x] Füge unter der Überschrift "Zutaten" eine ungeordnete Liste für die Zutaten deines Rezepts ein.
- [x] Füge unter der Überschrift "Zubereitung" eine geordnete Liste für die Zubereitung deines Rezepts hinzu

![mockup-image](/img/reference-image.png)

---

[//]: # (autograding info start)
## Ergebnisse


### Rezeptbuch

| Status | Prüfen |
| :-------------------------------------: | :--------------------------------------------------------------------------------------- |
| ![Status](../../blob/badges/.github/badges/autograding/status0.svg) | Index-Datei sollte angegebene Meta-Tags enthalten |
| ![Status](../../blob/badges/.github/badges/autograding/status1.svg) | Index.html Sollte einen 'title' Tag enthalten |
| ![Status](../../blob/badges/.github/badges/autograding/status2.svg) | Ein Bild sollte in index.html vorhanden sein, mit einer angegebenen Breite von 500px |
| ![Status](../../blob/badges/.github/badges/autograding/status3.svg) | H2-Tag mit dem Text 'ingredients' vorhanden |
| ![Status](../../blob/badges/.github/badges/autograding/status4.svg) | Zutaten sollte eine Unordered List mit einer Liste von Zutaten haben |
| ![Status](../../blob/badges/.github/badges/autograding/status5.svg) | H2-Tag mit dem Text 'Zubereitung' vorhanden |
| ![Status](../../blob/badges/.github/badges/autograding/status6.svg) | Vorbereitung sollte eine ungeordnete Liste mit einer Liste von Anweisungen haben |



[Ergebnisdetails](https://github.com/DigitalCareerInstitute/UIB-content-recipes/actions)

### Debugging deines Codes
> [Lesen der Testausgaben](https://github.com/DCI-EdTech/autograding-setup/wiki/Reading-test-outputs)

Es gibt zwei Möglichkeiten, um herauszufinden, warum Aufgaben nicht abgeschlossen werden können:
#### 1. Tests lokal ausführen
- Führe `npm install` aus
- Führe `npm test` im Terminal aus. Du wirst sehen, wo deine Lösung vom erwarteten Ergebnis abweicht.

#### 2. Überprüfen der Testausgabe auf GitHub
- Gehe auf die [Registerkarte Aktionen deines Übungsrepos](https://github.com/DigitalCareerInstitute/UIB-content-recipes/actions)
- Dort siehst du eine Liste mit den Testläufen. Klicke auf den obersten.
- Klicke auf "Autograding".
- Erweitere den Punkt 'Run DCI-EdTech/autograding-action@main'
- Hier siehst du alle Ausgaben des Testlaufs

[//]: # (autograding info end)
