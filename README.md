# Netzwerktopologien

Es handelt sich hierbei um ein digital gestaltetes Unterrichtsszenario für den Informatikunterricht zum Thema Netzwerktopologien. Erreichbar ist die Seite aktuell [hier](https://informatik.mkobrow.de/netzwerktopologien).

## Aufbau

1. Einführung in die Navigation
2. Einführung in Netzwerktopologien
   1. Bus
   2. Ring
   3. Stern
   4. Mesh
3. Aufgaben mit verschiedener Schwierigkeit

## Technische umsetzung

Die Seite wurde mittels [Docsify](https://docsify.js.org/#/) gestaltet. Docsify ermöglicht eine schnelle, visuell ansprechende, responsive Websitengestaltung mittels Markdown-Syntax. Zusätlich wird durch zahlreiche Plugins eine gewisse Flexibilität gewährleistet.

Dieses Projekt verwendet die Plugins
- docsify-image-caption für Bildunterschriften
- docsify-footer für den Lizenzfooter
- docsify-flexible-alerts für die Gestaltung der Definitions-, Hinweis-, Fragen- und Aufgabenkästchen.

Weiterhin wird für die interaktiven Elemente der Website [Vue.js](https://vuejs.org/) eingebunden.

Für die Quiz-Aufgabe wurde ein h5p Element verwendet, welches über ein externes Repository gehostet wird, welches allerdings private ist. Die h5p Datei mit Bildern findet sich aber trotzdem in diesem Repo unter [h5p-quiz](h5p-quiz/).

Gehostet wird die Website aktuell über die Github-Pages Umgebung dieses Repositorys.