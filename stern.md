# Sterntopologie

![Bild eines Stern-Netzwerkes](https://upload.wikimedia.org/wikipedia/commons/5/53/Netzwerktopologie_Stern.png 'https://commons.wikimedia.org/wiki/File:Netzwerktopologie_Stern.png')

## Beschreibung

- alle Geräte sind mit einem zentralen Knoten verbunden
- zentraler Knoten ist meist ein sogenannter **Switch**

> [!HINWEIS]
> Ein Switch ist ein Netzwerkgerät, welches Daten von einem Sender zum entsprechenden Empfänger weiterleiten kann.

## Kriterienuntersuchung

- **Skalierbarkeit**
  - Erweiterung, Wegnahme von Geräten einfach
- **Fehlertoleranz**
  - Ausfall von Rechnern egal
  - Switch als zentrale Verzweigung bietet allerdings Fehlerpotential
- **Verkabelungsaufwand**
  - jeder Rechner ein Kabel plus Switch als Zentrales Element → schlechter als Ring

<center>

|                     | Bus | Ring | Stern |
|---------------------|-----|------|-------|
| Skalierbarkeit      | +   | ++   | ++    |
| Fehlertoleranz      | +   | -    | +     |
| Verkabelungsaufwand | ++  | +    | -     |

</center>
