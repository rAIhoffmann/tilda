# Pinguin im Eislabyrinth 🐧

Ein Labyrinth-Spiel für Kinder ab etwa 10 Jahren. Pinguin Pino hat sich im riesigen Eislabyrinth verlaufen und muss zurück zu seinem Iglu.

Das Spiel besteht aus einer einzigen Datei (`index.html`) und läuft ohne Installation in jedem modernen Browser, auch auf Tablet und Handy.

## Spielregeln

- **Nebel:** Man sieht nur die Umgebung des Pinguins. Die Karte oben rechts merkt sich, wo man schon war.
- **Wände** aus Schnee kann man nicht durchqueren.
- **Wassergräben** kann man überspringen. Die Zahl der Sprünge ist aber begrenzt.
- **Fische** liegen in Sackgassen versteckt und geben je einen Extra-Sprung.
- **Tunnel** führen zum Tunnel mit der gleichen Farbe, oft weit entfernt.
- **Iglu** ist das Ziel.

8 Level von 29 × 21 bis 89 × 61 Feldern. Jedes Level ist immer gleich aufgebaut, damit man es wiederholen und die Bestzeit verbessern kann. Fortschritt und Bestzeiten speichert der Browser lokal.

## Steuerung

| Aktion | Tastatur | Touch |
|---|---|---|
| Laufen | Pfeiltasten oder W A S D | Steuerkreuz unten links |
| Springen | Leertaste | Knopf „Springen“ |
| Große Karte | M | Karte antippen |
| Level neu starten | R | Knopf „Neu“ |

## Lokal spielen

`index.html` herunterladen und per Doppelklick im Browser öffnen.

## Auf GitHub Pages veröffentlichen

1. Neues Repository auf GitHub anlegen, z. B. `pinguin-eislabyrinth`.
2. Die Dateien dieses Ordners hochladen („Add file“ → „Upload files“) oder per Git:
   ```bash
   git init
   git add .
   git commit -m "Pinguin im Eislabyrinth"
   git branch -M main
   git remote add origin https://github.com/<dein-name>/pinguin-eislabyrinth.git
   git push -u origin main
   ```
3. Im Repository unter **Settings → Pages** bei „Source“ **Deploy from a branch** wählen, Branch `main`, Ordner `/ (root)`, speichern.
4. Nach ein bis zwei Minuten läuft das Spiel unter
   `https://<dein-name>.github.io/pinguin-eislabyrinth/`

## Anpassen

Die wichtigsten Stellschrauben stehen oben im Skript in `index.html`:

- `LEVELS`: Name und Größe jedes Levels (`cw` × `ch` sind Zellen, das Spielfeld hat `2·cw+1` × `2·ch+1` Felder).
- `VIEW_R`: Sichtweite des Pinguins im Nebel (Standard 4).
- In `genLevel()`: Anzahl Wassergräben, Tunnel, Fische und Start-Sprünge.

## Lizenz

MIT, siehe [LICENSE](LICENSE).
