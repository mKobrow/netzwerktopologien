# Aufgaben

<div v-if="!showMeshSolution">

Bitte schaue dir zuerst die Inhalte an.

</div>
<div v-if="showMeshSolution && schwierigkeiten==''">

Wie bist du mit der Aufgabe zu den Mesh-Netzwerken zurecht gekommen?

<select name="schwierigkeiten" v-model="schwierigkeiten">
    <option value="">Bitte auswählen!</option>
    <option value="0">die Aufgabe war leicht</option>
    <option value="1">ich hatte Schwierigkeiten</option>
</select>
</div>

<div v-if="schwierigkeiten=='1'">

> [!AUFGABE]
> Löse das Quiz. Bitte wechsel währenddessen nicht auf eine andere Seite, sonst geht dein Fortschritt verloren. Falls du etwas nachschauen willst, öffne diese Seite in einem neuen Tab oder Fenster erneut.

<iframe src="https://informatik.mkobrow.de/h5pApplets/NetzwerktopologieErkennen/?embed=true" width="1098" height="705" frameborder="0" allowfullscreen="allowfullscreen"></iframe>
<script src="https://h5p.org/sites/all/modules/h5p/library/js/h5p-resizer.js" charset="UTF-8"></script>

Bist du schon vor Ende der Zeit fertig? Versuche dich doch noch an einer schwereren Aufgabe!

<button v-on:click="schwierigkeiten='0'">Klick mich!</button>
</div>

<div v-if="schwierigkeiten=='0'">

> [!AUFGABE]
> 1. Überprüfe, ob du eine oder mehrere der kennengelernten Topologien in der in der Gruppenarbeit erstellten Kommunikationsstruktur für eure Klasse wiederfindest. Beschreibe, wo und wie diese Topologien genau vorkommen.
> 2. Übertrage die folgenden Topologien auf die Kommunikation in deiner Klasse. Beschreibe jeweils, welche Probleme auftreten können.
>    1. Ringtopologie
>    2. Sterntopologie
>    3. Meshtopologie 


</div>