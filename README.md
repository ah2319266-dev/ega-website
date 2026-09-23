# EGA Atelier — Vertriebsseite

Statische Website für die EGA Damenschuh-Kollektion (Tabi-Silhouette mit geteilter
Zehenpartie, 100 % Leder, Handarbeit, Größe 35–43, bis zu 80 Farben).

## Inhalt

- `index.html` — die komplette Seite (HTML, CSS und JS in einer Datei, keine Build-Schritte)
- `img/` — 22 Produktaufnahmen, auf 4:5 normiert
- `render.yaml` — Blueprint für Render (Static Site)

## Lokal ansehen

```
python3 -m http.server 4173
```

Dann http://localhost:4173 öffnen.

## Deployment auf Render

1. Render-Dashboard → **New → Static Site**
2. Dieses Repository verbinden
3. Publish Directory: `.` — Build Command bleibt leer
4. Deploy

Alternativ **New → Blueprint** wählen, dann liest Render `render.yaml` direkt aus.

## Vor dem Livegang anpassen

- Kontaktadresse `handel@ega-atelier.example` durch die echte E-Mail ersetzen
  (kommt an vier Stellen in `index.html` vor)
- Preise: aktuell Platzhalter-UVPs im `P`-Array in `index.html`
- Impressum und Datenschutz ergänzen (Pflicht für gewerbliche Seiten in DE)
