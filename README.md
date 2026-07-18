# SiQ GmbH — Website-Relaunch (Prototyp)

Statische Website, kein Build-Schritt nötig (reines HTML/CSS/JS).

## Enthalten
- `index.html` — die komplette Seite
- `abb01.jpg`, `abb02.jpg`, `abb03.jpg` — die drei Abbildungen
- `vercel.json` — minimale Konfiguration für ein statisches Deployment

## So richtest du es ein

### 1. Bei GitHub hochladen
1. Neues Repository auf github.com anlegen (z. B. `siq-website`), **ohne** README/gitignore-Vorauswahl.
2. Auf der leeren Repo-Seite auf "uploading an existing file" klicken.
3. Alle vier Dateien aus diesem Ordner per Drag & Drop hochladen.
4. Commit bestätigen ("Commit changes").

### 2. In Vercel importieren
1. Auf vercel.com einloggen → "Add New" → "Project".
2. Das gerade erstellte GitHub-Repo auswählen ("Import").
3. Vercel erkennt es als statisches Projekt (kein Framework nötig) — Build Command und Output Directory leer lassen.
4. "Deploy" klicken.

Nach ca. 30–60 Sekunden ist die Seite unter einer `*.vercel.app`-URL live.

## Hinweis
Die Bilder sind aktuell einfache JPGs im Root-Verzeichnis. Für den produktiven Einsatz ggf. in einen `/public`-Ordner verschieben und Pfade in `index.html` entsprechend anpassen — für dieses Setup ist Root aber unproblematisch.
