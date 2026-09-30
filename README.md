# Notizen-App

Eine Notiz-App als einzelne Webseite: Notizen, Checklisten, Tags, Kalender, Bilder, Papierkorb, Erinnerungen, Diktieren, PIN-Sperre und Sicherung. Alle Daten bleiben im Browser des Geräts.

## Auf GitHub Pages veröffentlichen

1. Auf github.com ein neues Repository anlegen (Public).
2. Über „Add file" und „Upload files" diese Dateien hochladen: `index.html`, `manifest.json`, `sw.js`, `icon-192.png`, `icon-512.png`.
3. Im Repository unter „Settings" und „Pages" den Branch `main` mit dem Ordner `/ (root)` auswählen und speichern.
4. Nach ein bis zwei Minuten ist die App unter `https://DEIN-NAME.github.io/REPOSITORY-NAME/` erreichbar.

## Als App auf dem Handy

- iPhone (Safari): Teilen-Symbol, dann „Zum Home-Bildschirm".
- Android (Chrome): Menü, dann „App installieren" oder „Zum Startbildschirm hinzufügen".

Nach dem ersten Öffnen läuft die App auch ohne Internet.

## Hinweise

- Die Notizen liegen nur im Browser dieses Geräts. Erstelle regelmäßig eine Sicherung (ganz unten in der App).
- Der Name der App steht in `manifest.json` und in `index.html` (Titel und Sperrbildschirm).
