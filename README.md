# Verkehrsrechner

Rechner für Fahrzeugtechnik in der Schweiz, als Web-App im Browser – ohne Installation, auf PC und iPad.

**App öffnen:** https://morthuras.github.io/verkehrsrechner/

## Rechner

| Rechner | Grundlage |
|---|---|
| Anhängerkupplung: Mindest-D-Wert und maximale Anhängelast | UN ECE R55 |
| Felgen und Spur: Mindest-Einpresstiefe, Distanzscheiben, resultierende Spur (VA/HA) | höchstens 1 % Spuränderung pro Rad |
| Achslasten LKW: zulässiges Gesamtgewicht und Einträge Ziffer 243 (2–5 Achsen) | VTS Art. 95 |

## Dateien

- `index.html` – die veröffentlichte App als eine einzige Datei (Bild eingebettet). Diese Datei liefert GitHub Pages aus.
- `src/verkehrsrechner.html` – Quelldatei zum Bearbeiten.
- `src/hintergrund.jpg` – Hintergrundbild der Startseite.

## Aktualisieren

1. `src/verkehrsrechner.html` bearbeiten.
2. Daraus eine neue `index.html` erzeugen: Bild als Base64 einbetten und in ein vollständiges HTML-Gerüst setzen.
3. `index.html` und die geänderten Dateien in `src/` hochladen.

Eingaben werden nur im Browser des jeweiligen Geräts gespeichert, nicht auf GitHub.
