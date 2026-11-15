# 5×5 Trainer (PWA)

Statische Web-App, kein Server nötig. Alle Daten bleiben auf dem Gerät.

## Veröffentlichen (GitHub Pages, kostenlos)
1. Auf github.com ein neues öffentliches Repository anlegen, z. B. `5x5-trainer`.
2. Alle Dateien dieses Ordners hochladen (Add file > Upload files).
3. Settings > Pages > Branch `main`, Ordner `/ (root)` > Save.
4. Nach ca. einer Minute ist die App unter `https://<name>.github.io/5x5-trainer/` erreichbar.

## Installieren
- iPhone: Link in Safari öffnen, Teilen, "Zum Home-Bildschirm".
- Android: Link in Chrome öffnen, Menü, "App installieren".

## Update veröffentlichen
In `sw.js` die Zahl in `CACHE = "5x5-v1"` erhöhen, sonst sehen Nutzer die alte Version.

## Vor dem Weitergeben
Impressum und Datenschutzhinweis ergänzen, wenn du die App öffentlich anbietest.
