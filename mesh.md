# Meshtopologie

![Bild eines Mesh-Netzwerkes](images/Meshtopologie.svg 'Mesh-Netzwerk')

## Beschreibung

- jedes Gerät des Netzwerks ist mit jedem anderen Gerät über ein separates Kabel verbunden
- theoretisch Kommunikation zwischen allen Geräten gleichzeitig möglich

## Kriterienuntersuchung

- **Skalierbarkeit**
  - Erweiterung schwierig, da zu jedem Rechner im Netz Kabel gelegt werden muss
- **Fehlertoleranz**
  - Ausfall eines Rechners irrelevant, da jeder zu jedem direkt verbunden ist
  - Ausfall eines Kabels verhindert nur Kommunikation zwischen zwei Rechnern
- **Verkabelungsaufwand**
  - sehr hoch

<center>

|                     | Bus | Ring | Stern | Mesh |
|---------------------|-----|------|-------|------|
| Skalierbarkeit      | +   | ++   | ++    |      |
| Fehlertoleranz      | +   | -    | +     |      |
| Verkabelungsaufwand | ++  | +    | -     |      |

</center>