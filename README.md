# RSVU-Beratung

AXA-ARAG Beratungsnavigator für den Unternehmensrechtsschutz – Version 18.

## GitHub Pages

Die Website ist für folgende Adresse vorbereitet:

`https://larsjenny.github.io/RSVU-Beratung/`

Alle Dateien und Ordner dieses Pakets müssen direkt in das Hauptverzeichnis
des GitHub-Repositorys `RSVU-Beratung` hochgeladen werden. Insbesondere müssen
`index.html`, `assets/` und `avb/` auf derselben Verzeichnisebene liegen.

Anschliessend in GitHub unter **Settings → Pages** folgende Einstellung wählen:

- Source: **Deploy from a branch**
- Branch: **main**
- Folder: **/(root)**

## Dateien

- `index.html`: vollständige Anwendung mit HTML, CSS, JavaScript und Beratungslogik
- `assets/industry/`: branchenspezifische Bilder
- `avb/`: vollständige und bausteinspezifische AVB-PDFs
- `.nojekyll`: verhindert eine unnötige Jekyll-Verarbeitung

## Hinweis zur Zugriffskontrolle

Ein gewöhnliches GitHub-Pages-Repository veröffentlicht die Website öffentlich.
Die Anwendung selbst enthält keine sichere Benutzeranmeldung. Eine bereits
heruntergeladene HTML-Datei kann unabhängig von der Website lokal geöffnet
werden.

