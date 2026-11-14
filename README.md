# Kleiner Expertengehilfe

*by Georg Winklmeier*

Rechner für Fahrzeugtechnik in der Schweiz, als Web-App im Browser – ohne Installation, auf PC und iPad.

**App öffnen:** https://morthuras.github.io/verkehrsrechner/

## Rechner

| Rechner | Grundlage |
|---|---|
| Anhängerkupplung: Mindest-D-Wert und maximale Anhängelast | UN ECE R55 |
| Felgen und Spur: Mindest-Einpresstiefe, Distanzscheiben, resultierende Spur (VA/HA) | höchstens 1 % Spuränderung pro Rad |
| Achslasten LKW: zulässiges Gesamtgewicht und Einträge Ziffer 243 (2–5 Achsen) | VTS Art. 95 |
| Zentralachsanhänger: Stützlast aus der Nutzlast, X-Wert der Ladefläche, Nutzlast (1–3 Achsen) | Richtwert 10 % bzw. 1000 kg |

## Dateien

- `index.html` – die veröffentlichte App als eine einzige Datei (Bild eingebettet). Diese Datei liefert GitHub Pages aus.
- `src/verkehrsrechner.html` – Quelldatei zum Bearbeiten.
- `src/hintergrund.jpg` – Hintergrundbild der Startseite.

## Aktualisieren

1. `src/verkehrsrechner.html` bearbeiten.
2. Mit `sync-github.ps1` (PowerShell, liegt lokal neben der Quelldatei) die `index.html` neu bauen und alle geänderten Dateien hochladen. Das Skript bettet das Bild als Base64 ein und überspringt unveränderte Dateien.
3. Alle geänderten Dateien landen in einem einzigen Commit, damit GitHub Pages nur einmal neu baut. Die Seite ist danach in der Regel nach 1–2 Minuten aktuell; ist die Seite noch alt, einmal neu laden.

Eingaben werden nur im Browser des jeweiligen Geräts gespeichert, nicht auf GitHub.
