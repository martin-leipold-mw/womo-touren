# Meine Womo-Touren – auf GitHub Pages veröffentlichen

Dieser Ordner enthält deine Touren-Seiten und eine `index.html`, die alle
verlinkt. Alle Links sind **relativ**, darum funktioniert die Verlinkung, solange
die Dateien **zusammen im selben Ordner** bleiben.

## In 5 Schritten online (kostenlos)

1. **GitHub-Konto** anlegen (falls noch nicht vorhanden): https://github.com
2. **Neues Repository** erstellen, z. B. Name `womo-touren`, Sichtbarkeit **Public**.
   („New repository“ → Name eingeben → „Create repository“.)
3. **Dateien hochladen:** im Repo auf **„Add file“ → „Upload files“** und den
   **kompletten Inhalt dieses Ordners** hineinziehen:
   - `index.html`
   - `Wochenende_Koenigssee.html`
   - `Wochenende_Oy-Mittelberg.html`
   - `.nojekyll` (unsichtbare Datei – bitte mit hochladen; verhindert Verarbeitungsfehler)
   Dann unten **„Commit changes“**.
4. **Pages aktivieren:** Repo → **Settings** → links **Pages** →
   *Source*: **„Deploy from a branch“**, *Branch*: **`main`**, Ordner **`/ (root)`** → **Save**.
5. Nach ~1 Minute ist deine Seite erreichbar unter:
   **`https://DEIN-BENUTZERNAME.github.io/womo-touren/`**
   Diese URL als Lesezeichen speichern – funktioniert auf allen Geräten.

## Neue Tour hinzufügen

1. Neue Touren-HTML (vom Camping-Planer erzeugt) in denselben Ordner/dasselbe Repo legen.
2. `index.html` neu erzeugen lassen (der Planer macht das auf Wunsch automatisch) und
   die aktualisierte `index.html` mit hochladen.
3. Änderungen committen – die Seite aktualisiert sich von selbst.

## Hinweise

- Die **Kartenkacheln** kommen live von OpenStreetMap – online sieht man die Karte,
  offline bleibt der Hintergrund grau (Marker & Plan funktionieren trotzdem).
- Dateinamen ohne Leerzeichen/Umlaute halten (z. B. `Wochenende_Koenigssee.html`),
  dann klappen die Links überall zuverlässig.
