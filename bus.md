# Bustopologie

![Bild eines Bus-Netzwerkes](images/bus.svg ':size=400 Schaubild Bustopologie')

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

<div class="vergleichstabelle">

|                     | Bus |
|---------------------|-----|
| Skalierbarkeit      | +   |
| Fehlertoleranz      | +   |
| Verkabelungsaufwand | ++  |

</div>

> [!FRAGE]
> Ist es in einem Bus-Netzwerk möglich eine Nachricht nur an speziell ein anderes Gerät zu senden, ohne dass die anderen Geräte sie lesen könnten?
