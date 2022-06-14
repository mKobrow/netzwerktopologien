# Meshtopologie

![Bild eines Mesh-Netzwerkes](images/mesh.svg ':size=300 Schaubild Meshtopologie')

## Beschreibung

- jedes Gerät des Netzwerks ist mit jedem anderen Gerät über ein separates Kabel verbunden
- theoretisch Kommunikation zwischen allen Geräten gleichzeitig möglich

## Kriterienuntersuchung

<div v-if="!showMeshSolution">
<div class="vergleichstabelle">

|                     | Bus | Ring | Stern | Mesh |
|---------------------|-----|------|-------|------|
| Skalierbarkeit      | +   | ++   | ++    |      |
| Fehlertoleranz      | +   | -    | +     |      |
| Verkabelungsaufwand | ++  | +    | -     |      |

</div>

> [!AUFGABE]
> Überlege dir anhand der vorgegangenen Kriterienuntersuchungen für Bus, Ring und Stern, inwiefern die Kriterien durch das Mesh erfüllt werden.
> 
> Notiere die Bewertungen und die Begründungen. Klicke danach auf den Lösungsknopf um meine Überlegungen dazu zu sehen.

<button class="Lösung" v-on:click="showMeshSolution = true">Lösung</button>

</div>

<div v-if="showMeshSolution">

- **Skalierbarkeit**
  - Erweiterung schwierig, da zu jedem Rechner im Netz Kabel gelegt werden muss
- **Fehlertoleranz**
  - Ausfall eines Rechners irrelevant, da jeder zu jedem direkt verbunden ist
  - Ausfall eines Kabels verhindert nur Kommunikation zwischen zwei Rechnern
- **Verkabelungsaufwand**
  - sehr hoch

<div class="vergleichstabelle">

|                     | Bus | Ring | Stern | Mesh |
|---------------------|-----|------|-------|------|
| Skalierbarkeit      | +   | ++   | ++    | -    |
| Fehlertoleranz      | +   | -    | +     | ++   |
| Verkabelungsaufwand | ++  | +    | -     | --   |

</div>

> [!AUFGABE]
> Erstelle dir eine Übersicht über die verschiedenen Netzwerktopologien im Hefter!
> 
> Übernehme dafür zuerst die Definition einer Netzwerktopologie und anschließend die Skizzen zu den jeweiligen Topologien. Übernehme außerdem die Definition der Kriterien, sowie die zusammenfassende Tabelle.


> [!HINWEIS]
> Wenn du deine Lösungen verglichen hast und die Übersicht für den Hefter erstellt hast, wechsle bitte in das nächste Kapitel "Aufgaben".

</div>

