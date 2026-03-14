# 🧱 bricked


**Virtueller LEGO-Editor im Browser — mit echten LEGO-Maßen und STL-Export für den 3D-Druck.**

[![Demo](https://img.shields.io/badge/Live%20Demo-GitHub%20Pages-red?style=flat-square)](https://mdhn27.github.io/bricked)

---

## Features

- **12 Steinformen** — von 1×1 Noppe bis 2×6 Brett, Standard- und Flachsteine
- **Rotation** — Steine um 90° drehen (Taste Q/E)
- **Kollisionserkennung** — keine überlappenden Steine
- **Undo / Redo** — unbegrenzt (Strg+Z / Strg+Y)
- **Mehrere Ebenen** — bis zu 30 Lagen (Taste `[` / `]`)
- **LEGO-Standard-Maße** — 1 Stud = 8 mm, Stein = 9,6 mm hoch, Platte = 3,2 mm
- **STL-Export** — direkt druckbares Binary-STL mit korrekten Noppen
- **Speichern / Laden** — `.bricked` JSON-Projektdatei
- **20 Farben**
- **Kamera** — Rechtsklick drehen, Scroll zoomen

## Steuerung

| Aktion | Eingabe |
|--------|---------|
| Stein setzen | Linksklick |
| Stein löschen | Rechtsklick-Modus + Klick |
| Kamera drehen | Rechtsklick + Ziehen |
| Zoom | Scrollrad |
| Rotation links | `Q` |
| Rotation rechts | `E` |
| Ebene rauf | `]` |
| Ebene runter | `[` |
| Rückgängig | `Strg+Z` |
| Wiederholen | `Strg+Y` |
| Speichern | `Strg+S` |


## LEGO-Maße (Referenz)

| Maß | Wert |
|-----|------|
| 1 Stud (Rasterabstand) | 8,0 mm |
| Stein-Höhe | 9,6 mm (= 3 Platten) |
| Platten-Höhe | 3,2 mm |
| Noppen-Radius | 2,4 mm |
| Noppen-Höhe | 1,7 mm |
| Wandstärke | 1,5 mm |

## STL & 3D-Druck

Die exportierte STL enthält alle Steine mit Noppen und echten LEGO-Proportionen.  
Empfohlene Druckeinstellungen:

- **Schichtdicke**: 0,2 mm oder weniger
- **Infill**: 20–40%
- **Material**: PLA, PETG
- **Slicer**: PrusaSlicer, Bambu Studio, Cura

> **Hinweis**: Die Steine sind nicht kompatibel mit echten LEGO-Steinen (Wandstärke und Toleranzen weichen ab). Für Kompatibilität müssen Toleranzen angepasst werden.

## Technologie

Rein browser-basiert, keine Installation, keine Dependencies außer:
- [Three.js r128](https://threejs.org/) — 3D-Rendering
- [Google Fonts](https://fonts.google.com/) — Nunito, Space Mono

## Lizenz

MIT — frei verwendbar, anpassbar, weiterzugeben.
