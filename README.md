<p align="center"><img src="logo.png" width="96" alt="Blattwerk"></p>

# Blattwerk

Fertigungszeichnungen aus 3D-Modellen und PDF-Zeichnungen – nach SN EN ISO. Für Windows.

## Herunterladen

**[→ Neueste Version](https://github.com/vogelmaurice18-sys/Blattwerk-Download/releases/latest)** – dort
`Blattwerk-Setup-<Version>.exe` herunterladen und starten.

- Windows 10 oder 11, 64 Bit, rund 500 MB Platz
- keine Administratorrechte nötig (Blattwerk wird nur für den angemeldeten Benutzer installiert)
- **Windows-Warnung beim ersten Start:** Das Setup ist noch nicht digital signiert. Windows zeigt deshalb
  «Der Computer wurde durch Windows geschützt». Auf **«Weitere Informationen» → «Trotzdem ausführen»** klicken.
- Prüfsumme: neben dem Setup liegt die Datei `.sha256` (SHA-256 des Setups)

## Neue Versionen

Blattwerk meldet beim Start (höchstens einmal am Tag), wenn es hier eine neuere Version gibt. «Herunterladen»
öffnet das neue Setup – einfach ausführen, es ersetzt die alte Version. Zeichnungen und Einstellungen bleiben
erhalten. Ausschalten: Einstellungen › Allgemein. Von Hand: Menü › Über Blattwerk › «Nach Updates suchen».

## Was Blattwerk kann

- STEP, IGES, BREP, STL, OBJ, 3MF öffnen – Ansichten, Schnitte und Einzelheiten entstehen per Klick
- Bemassen mit einem Klick auf die Kante, Auto-Mass, Ketten- und Bezugsmasse
- Toleranzen und Passungen (ISO 286), Form- und Lagetoleranzen, Oberflächen-, Kanten- und Schweisssymbole
- PDF-Zeichnungen öffnen und bearbeitbar machen
- Export als PDF, DXF, SVG und PNG (DWG mit dem kostenlosen ODA File Converter)
- KI-Prüfung der Zeichnung (mit eigenem API-Schlüssel)

## Deinstallieren

Windows-Einstellungen › Apps › Blattwerk › Deinstallieren. Ihre Zeichnungen bleiben erhalten.

## Fehler und Wünsche

Hier unter [Issues](https://github.com/vogelmaurice18-sys/Blattwerk-Download/issues) melden.

## Lizenz

Blattwerk ist kostenlos nutzbar; der Quellcode ist nicht öffentlich. Blattwerk benutzt freie Programmteile
(u. a. Qt, Open CASCADE, PDFium). Deren Lizenzen liegen im Programmordner unter `Lizenzen` und sind in Blattwerk
unter Menü › Über Blattwerk › «Lizenzen» zu finden.
