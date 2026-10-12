# Eichis Schatzinsel

Eine Schatzsuche im Browser für die 5. Klasse am Gymnasium. Eichi das Eichhörnchen läuft über eine grüne Insel und löst an 8 Stationen Rätsel: Mathe, Englisch, Deutsch, Biologie, ein Labyrinth und ein Fehlersuchbild. Jede Station bringt einen Buchstaben, und das Lösungswort verrät, wo der Schatz vergraben ist.

## Auf GitHub Pages veröffentlichen

1. Auf github.com ein neues Repository anlegen, z. B. `schatzinsel` (öffentlich).
2. Alle Dateien aus diesem Ordner hochladen: **Add file → Upload files**, Dateien hineinziehen, **Commit changes**.
3. **Settings → Pages**: Unter *Build and deployment* die Quelle **Deploy from a branch** wählen, Branch **main**, Ordner **/ (root)**, **Save**.
4. Nach ein bis zwei Minuten läuft das Spiel unter `https://<dein-benutzername>.github.io/schatzinsel/`.

Per Kommandozeile geht es auch:

```bash
git init && git add . && git commit -m "Eichis Schatzinsel"
git branch -M main
git remote add origin https://github.com/<dein-benutzername>/schatzinsel.git
git push -u origin main
```

## Auf dem iPhone oder iPad wie eine App nutzen

Seite in Safari öffnen → Teilen-Symbol → **Zum Home-Bildschirm**. Das Spiel startet dann im Vollbild mit eigenem Icon.

## Spielstand

Der Spielstand wird automatisch im Browser des Geräts gespeichert: gelöste Stationen, gesammelte Buchstaben und Eichis Position auf der Insel. Man kann jederzeit aufhören und später weiterspielen.

Gut zu wissen:

- Der Spielstand gilt pro Gerät und Browser. Auf einem anderen Gerät beginnt das Spiel neu.
- Auf dem iPhone haben Safari und die Version auf dem Home-Bildschirm getrennte Speicher. Am besten immer auf demselben Weg spielen.
- Im privaten Surfmodus wird nichts dauerhaft gespeichert.
- Neu starten geht über den **?**-Knopf oben rechts → **Spiel neu starten**.

## Dateien

| Datei | Zweck |
|---|---|
| `index.html` | Das komplette Spiel (eine Datei, keine Installation nötig) |
| `manifest.webmanifest` | App-Name und Icons für den Home-Bildschirm |
| `icon-*.png` | App-Icons |
| `.nojekyll` | Sorgt dafür, dass GitHub Pages die Dateien unverändert ausliefert |
