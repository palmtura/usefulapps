# macOS App Bundle Website (Stak)

Statische Landingpage für ein macOS-Produktivitäts-App-Bundle.
Schwarz/Weiß-Design mit animierten Gradient-Headlines, Live-Suche, Kategoriefiltern,
3 Layout-Ansichten (Grid / List / Gallery) und individuellen App-Unterseiten.

## Dateien

- **`index.html`** — Fertige, eigenständige Website. Alles eingebettet (Fonts, Skripte, Bild),
  offline lauffähig. **Das ist die Datei, die live geht.**
- `Stak Bundle.dc.html` — Quelldatei (bearbeitbar). Bei Änderungen diese editieren und neu bündeln.
- `image-slot.js`, `support.js` — Hilfsskripte (nur für die Quelldatei; in `index.html` bereits eingebettet).
- `uploads/` — Bild- und Icon-Assets.

## Auf Hostinger veröffentlichen

### Variante A — direkt (schnellster Weg)
1. Hostinger → **File Manager** öffnen.
2. In den Ordner **`public_html`** wechseln.
3. **`index.html`** dort hochladen (vorhandene `index.html` ggf. ersetzen).
4. Domain aufrufen — fertig.

### Variante B — über GitHub
1. Neues Repository auf github.com anlegen (z. B. `stak-bundle`).
2. Diese Dateien hochladen (mindestens `index.html`).
3. In Hostinger unter **Git** das Repository verbinden und in `public_html` deployen.

## Buy-Button / App-Store-Link

Alle „Get the Bundle"-Buttons zeigen aktuell auf einen Platzhalter
(`https://www.apple.com/app-store/`). Sobald der echte App-Store-Link vorliegt,
in der Quelldatei ersetzen und neu bündeln.
