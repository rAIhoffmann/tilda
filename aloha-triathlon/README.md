# Aloha Triathlon

Ein 3D-Inselspiel im Browser: Du lebst auf Hawaii, arbeitest als Reitlehrerin und trainierst für Triathlon und Ironman.

## Was es im Spiel gibt

- **Insel** mit Vulkan, Ringstraße, Strand, Verkehr und Straßen-Navi
- **Villa zum Reingehen** mit Küche (Kühlschrank, Herd, Esstisch), Fitnessraum mit Yogamatte, Wohnzimmer und Schlafzimmer
- **Auto** mit Tank, Tankstelle, Werkstatt und Unfällen
- **Reitstall:** Reitstunden mit 3–10 Reitschülern, Longe, Gerte, Longierpeitsche und Tonnen, dazu ein eigener Springparcours
- **Sportplatz:** Laufen, Schwimmen, Radfahren, Fußball, Tennis, Golf, Minigolf und Autorennbahn
- **Triathlon-Strand:** Sprint-Triathlon und Ironman gegen drei Gegnerinnen, dazu eine Übungsstation für die Wechselzone
- **Mitmenschen:** Trainerin Myla (samstags), Kai und Noelani
- **Handy:** Möbel-Shop, Supermarkt, Werkstatt, Anrufen
- **Kleiderschrank** mit täglich neuer Kollektion und Frisuren

## Steuerung

- **Handy/Tablet:** Joystick unten links, Aktionsknöpfe unten rechts
- **Computer:** WASD oder Pfeiltasten, `E` für Aktion, `F` für Auto ein- und aussteigen, Leertaste zum Springen beim Reiten

Der Spielstand wird im Browser gespeichert (localStorage), auf jedem Gerät separat.

## Auf GitHub Pages veröffentlichen

1. Auf GitHub ein neues Repository anlegen, z. B. `aloha-triathlon`.
2. Die Dateien `index.html`, `README.md` und `.nojekyll` hochladen („Add file“ → „Upload files“).
3. Im Repository unter **Settings → Pages** bei „Branch“ `main` und den Ordner `/ (root)` auswählen und speichern.
4. Nach ein bis zwei Minuten läuft das Spiel unter `https://<dein-name>.github.io/aloha-triathlon/`.

## Technik

- Eine einzige Datei (`index.html`), kein Build-Schritt nötig
- 3D mit [three.js r128](https://threejs.org/) (wird von cdnjs geladen)
- Schrift „Baloo 2“ von Google Fonts
- Zum lokalen Testen einfach `index.html` im Browser öffnen
