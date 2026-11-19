# 🐱🏝️ Katzen-Inseln

Ein Abenteuer-Spiel für Handy und Browser: Eine Katze fliegt von Insel zu Insel, sammelt Münzen und meistert Parcours, Bahngleis-Verfolgungsjagden, Suchbilder – und entkommt dem Labyrinth des Ungeheuers.

## Spielen

Einfach `index.html` im Browser öffnen – oder über GitHub Pages spielen (siehe unten).
Auf dem iPhone: In Safari öffnen → Teilen → **„Zum Home-Bildschirm“**. Dann startet das Spiel wie eine App im Vollbild.

## So geht's

| Was | Wie |
|---|---|
| Laufen | Finger aufs Bild legen und ziehen (am Computer: Pfeiltasten) |
| Fliegen / Landen | Runder Knopf unten rechts (am Computer: Leertaste) |
| Parcours 🧗 | Wisch hoch = springen, Wisch runter = rutschen, an Seile springen |
| Bahngleise 🚂 | Wisch links/rechts = Gleis wechseln, hoch = springen, runter = ducken, Doppeltipp = Schutzschild |
| Labyrinth 👹 | In eine Richtung wischen, Katze läuft bis zur nächsten Kreuzung |
| Suchbild 🔍 | 15 Unterschiede antippen |
| Ponyhof 🐴 | Pferd aussuchen, führen, putzen, satteln – dann Wald, Reithalle oder Reitplatz. Manchmal bist du die Reitlehrerin! |
| Bibliothek 📚 | Buch aussuchen, in die Geschichte eintauchen und selbst entscheiden |
| Sportplatz 🏃 | Wettrennen: abwechselnd Links/Rechts tippen |
| Leichtathletik 🏅 | Hürdenlauf, Weitsprung, Hochsprung, Ballwurf |
| Tierinsel 🦁 | Tiere besuchen und richtig füttern |
| Verwandlungs-Insel 🪄 | Für 60 Sekunden Vogel, Delfin, Gepard oder Maus sein |

Münzen gibt es überall. Im 🛒 Laden kann man bessere Segel kaufen, um ferne Inseln zu erreichen – bis zur Goldenen Insel 👑.

Der Spielstand wird im Browser gespeichert (localStorage).

## Auf GitHub Pages veröffentlichen

1. Neues Repository auf GitHub anlegen (z. B. `katzen-inseln`, öffentlich).
2. **Add file → Upload files** und alle Dateien aus diesem Ordner hochladen.
3. **Settings → Pages** → Source: *Deploy from a branch* → Branch `main`, Ordner `/ (root)` → **Save**.
4. Nach ein bis zwei Minuten ist das Spiel erreichbar unter
   `https://<dein-github-name>.github.io/katzen-inseln/`

## Dateien

- `index.html` – das komplette Spiel (HTML, CSS und JavaScript in einer Datei, keine Abhängigkeiten)
- `manifest.json`, `icon-180.png`, `icon-512.png` – App-Symbol für den Home-Bildschirm
