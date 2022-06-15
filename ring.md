# Ringtopologie

![Bild eines Ring-Netzwerkes](images/ring.svg ':size=400 Schaubild Ringtopologie')

## Beschreibung

- ein Gerät im Netzwerk ist immer mit zwei anderen Geräten verbunden
- der erste Rechner ist mit dem zweiten Rechner verbunden, der zweite Rechner ist mit dem dritten Rechner verbunden, usw. bis ein Rechner wieder mit dem ersten Rechner verbunden ist
- auch hier wird eine Kontrolle benötigt, wer wann Daten durch den Ring schicken darf

## Kriterienuntersuchung

- **Skalierbarkeit**
  - Erweiterung sehr einfach durch "Einklemmen" zwischen zwei Rechnern
- **Fehlertoleranz**
  - Ausfall eines Rechners oder Kabels führt direkt zu totalausfall des Netzes
- **Verkabelungsaufwand**
  - immernoch recht gut

<div class="vergleichstabelle">

|                     | Bus | Ring |
|---------------------|-----|------|
| Skalierbarkeit      | +   | ++   |
| Fehlertoleranz      | +   | -    |
| Verkabelungsaufwand | ++  | +    |

</div>

> [!FRAGE]
> Angenommen n sei die Anzahl an Geräten in einem Ring-Netzwerk. Wie viele Kabel werden für dieses Netzwerk benötigt?