# Ringtopologie

![Bild eines Ring-Netzwerkes](https://upload.wikimedia.org/wikipedia/commons/7/71/Netzwerktopologie_Ring.png 'https://upload.wikimedia.org/wikipedia/commons/7/71/Netzwerktopologie_Ring.png')

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
  - immernoch recht gut, für jeden Rechner ein Kabel, plus ein Kabel um den Ring zu schließen

<center>

|                     | Bus | Ring |
|---------------------|-----|------|
| Skalierbarkeit      | +   | ++   |
| Fehlertoleranz      | +   | -    |
| Verkabelungsaufwand | ++  | +    |

</center>
