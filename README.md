# Galabau Essen – statische One-Page
Diese Dateien enthalten eine einfache, schnelle **HTML/CSS**-Version der Website. Du kannst sie sofort auf **GitHub Pages** hosten oder per FTP auf deinen Webspace laden.

## Dateien
- `index.html` – die Website
- `assets/logo.png` – Logo (Platzhalter, bitte ersetzen)
- `assets/hecke.jpg` – Hero-Hintergrund (Platzhalter, bitte ersetzen)

> Tipp: Wenn du (noch) keine Bilder hast, bleibt ein schöner Verlauf als Fallback aktiv.

## 1) Anpassen
- Ersetze in `index.html` unter **Kontakt** die Telefonnummer und E-Mail.
- Ersetze die Platzhalterbilder in `assets/` durch deine eigenen Dateien (gleiche Dateinamen verwenden).

## 2) GitHub Pages veröffentlichen (kostenlos)
1. GitHub-Account erstellen (falls nicht vorhanden).
2. Neues Repository anlegen, z. B. `galabauessen-website`.
3. Die Dateien (`index.html` und Ordner `assets/`) hochladen und committen.
4. Im Repo: **Settings → Pages** → *Build and deployment*: **Source = Deploy from a branch**.
5. **Branch = main**, **Folder = /(root)** auswählen → **Save**.  
   GitHub baut jetzt automatisch eine Seite unter `https://<DEIN-GITHUB-NAME>.github.io/galabauessen-website/`.
6. Öffne die URL (siehe **Environments → github-pages → View deployment**).

## 3) Eigene Domain verbinden (`galabauessen.de`)
1. Im Repo **Settings → Pages → Custom domain**: `galabauessen.de` eintragen und speichern (GitHub legt automatisch eine `CNAME` an).
2. Bei deinem Domain-Anbieter (IONOS/Strato/…):
   - **www** → CNAME auf `<DEIN-GITHUB-NAME>.github.io`
   - **Apex-Domain** (`galabauessen.de` ohne www): Entweder A-Records auf die GitHub-Pages-IP-Adressen laut GitHub-Dokumentation **oder** einen ALIAS/ANAME/Flattening-Eintrag, falls dein DNS-Anbieter das unterstützt.
3. Warte, bis die DNS-Änderungen aktiv sind (meist 10–60 Min.).
4. In **Settings → Pages** „**Enforce HTTPS**“ aktivieren.

## 4) Optional: Direktes Hosting beim Hoster
- Lade `index.html` + `assets/` per FTP in das Webverzeichnis deiner Domain hoch (z. B. `htdocs/`).
- Fertig – kein Build, keine Datenbank nötig.

Viel Erfolg! ✂️🌿
