# Tulpenstrasse 15, Wohnung 5

**Wichtig:** Der Inhalt dieses Ordners kommt ins Repository, nicht der Ordner selbst.
Die `index.html` muss im Repository ganz oben liegen, nicht in einem Unterordner.
Pages einschalten unter Settings, Pages, Source "Deploy from a branch", Branch `main`, Ordner `/ (root)`.

Dieser Ordner ist vollstaendig und unabhaengig von den anderen Wohnungen.

    index.html      die Seite
    unterlagen/     die PDF Dokumente dieser Wohnung

Beides zusammen in ein Repository hochladen, GitHub Pages einschalten, fertig.
Der Ordner `unterlagen` muss neben der `index.html` liegen.

Soll er anders heissen, in der `index.html` nur diese eine Zeile aendern:

    var DOKBASE='unterlagen/';

Die Downloads funktionieren erst auf der veroeffentlichten Seite. Per Doppelklick
von der Festplatte geoeffnet sperrt der Browser den Zugriff auf die Nachbardateien.
