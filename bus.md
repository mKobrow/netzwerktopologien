# Bustopologie

![Bild eines Bus-Netzwerkes](https://upload.wikimedia.org/wikipedia/commons/3/32/Netzwerktopologie_Bus.png 'https://commons.wikimedia.org/wiki/File:Netzwerktopologie_Bus.png')

## Beschreibung

- Alle Computer sind direkt mit einem einzigen Kabel (dem Bus) miteinander verbunden.
- Wird ein Signal gesendet, so kann es jedes Gerät, das am Bus angeschlossen ist lesen.
- Es muss koordiniert werden, wer wann senden darf, damit es nicht zu Störungen kommt.

## Kriterienuntersuchung

- **Skalierbarkeit**
  - Erweiterung grundsätzlich einfach möglich, jedoch wird bei größeren Netzen schnell der Platz auf dem Bus knapp
- **Fehlertoleranz**
  - Ausfall eines Rechners ist egal, Kommunikation im Netz trotzdem weiter möglich
  - bei Beschädigung des Buskabels ist aber keine Kommunikation mehr möglich
- **Verkabelungsaufwand**
  - sehr gering

<center>

|                     | Bus |
|---------------------|-----|
| Skalierbarkeit      | +   |
| Fehlertoleranz      | +   |
| Verkabelungsaufwand | ++  |

</center>
