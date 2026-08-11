# Tulpenstrasse 15, Wohnung 5

## Hochladen

Ein eigenes Repository fuer diese Wohnung anlegen. Dann im Repository auf
"Add file", danach "Upload files", und in das Fenster **beides zusammen** ziehen:

    index.html
    unterlagen        (der ganze Ordner)

Wichtig: nicht den Ordner "wohnung-5" hochladen, sondern seinen Inhalt.
Die index.html muss im Repository ganz oben liegen.

## Pages einschalten

Settings, dann Pages. Bei Source "Deploy from a branch" waehlen,
Branch `main`, Ordner `/ (root)`. Speichern. Der erste Aufbau
dauert ein bis zwei Minuten, danach steht die Adresse oben auf der Seite.

## Groessen

Keine Datei ist groesser als rund 4 MB. Der Weblader von GitHub nimmt
einzelne Dateien bis 25 MB, das ist also unproblematisch.
Die Seite selbst laedt beim Besucher mit rund 2,5 MB.

## Falls der Ordner anders heissen soll

In der index.html steht im Skript genau eine Zeile:

    var DOKBASE='unterlagen/';

Nur diese aendern. Der Schraegstrich am Ende muss bleiben.

## Hinweis

Die Dokumente werden erst auf der veroeffentlichten Seite geladen.
Oeffnest du die index.html per Doppelklick von der Festplatte, sperrt der
Browser den Zugriff auf den Nachbarordner. Die Seite erscheint, die
Downloads funktionieren dort aber nicht.
