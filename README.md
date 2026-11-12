# ⚽ 1x1 Champions Arena

Ein Fußball-Lernspiel für das kleine Einmaleins (2. Klasse Volksschule) – für zwei Kinder, Ilian und Johan.

## ▶️ Jetzt spielen

**👉 [Spiel im Browser öffnen](https://michaelquehenberger.github.io/1x1/)**

Das Spiel läuft direkt im Browser, auf PC, Tablet und Handy. Man braucht keine Installation und kein Konto.

> Der Link funktioniert, sobald GitHub Pages eingeschaltet ist (siehe [unten](#-online-stellen-github-pages)).

**Ohne Internet:** [`index.html`](index.html) herunterladen und mit Doppelklick im Browser öffnen.

## 🎮 So wird gespielt

1. **Kapitän wählen:** Jedes Kind sucht sich seinen Lieblingsspieler aus.
2. **Schwierigkeitsstufe wählen:**

   | Stufe | Einmaleins-Reihen |
   |---|---|
   | 🥉 Rookie | 1er, 2er, 5er, 10er |
   | 🥈 Profi | 1er, 2er, 3er, 4er, 5er, 10er |
   | 🥇 Weltmeister | 2er bis 10er (alle Reihen) |

3. **Spielmodus wählen:**
   - ⚔️ **Elfmeter-Duell:** Die Kinder schießen abwechselnd, jedes hat 10 Schüsse. Wer mehr Tore hat, gewinnt den Pokal.
   - 🤝 **Team-Pokal:** Beide spielen zusammen, bis das Team 10 Tore geschossen hat.
4. **Aufgabenart wählen:**
   - 🔢 **Rechnen:** klassische Aufgaben wie `4 × 5 = ?`
   - 📖 **Textaufgaben:** kurze Fußball-Rechengeschichten (Sticker, Fanbus, Torwand, Pizza nach dem Sieg …). Ein **Bild mit Gruppen** zeigt die Aufgabe, z.B. 4 Kästchen mit je 5 ⚽. Mit **🔊 Vorlesen** liest der Browser die Geschichte vor. Nach der Antwort erscheint die passende Rechnung (`📝 4 × 5 = 20`).
   - 🎲 **Gemischt:** Rechenaufgaben und Textaufgaben abwechselnd.
5. **ANPFIFF!** drücken.
6. Für jede Aufgabe die richtige von 4 Antworten antippen.
   - Richtig: **TOR!** ⚽
   - Falsch: Die richtige Lösung wird grün angezeigt.
7. Am Ende gibt es mit **REVANCHE!** ein neues Spiel.

## 🌐 Online stellen (GitHub Pages)

Einmalig einrichten, damit der Link oben funktioniert:

1. Im Repository auf **Settings → Pages** gehen ([direkt hier](https://github.com/michaelquehenberger/1x1/settings/pages)).
2. Bei **Source** „Deploy from a branch“ wählen.
3. Branch **`main`** und Ordner **`/ (root)`** auswählen und auf **Save** klicken.
4. Nach 1–2 Minuten ist das Spiel unter https://michaelquehenberger.github.io/1x1/ erreichbar.

**Tipp:** Am Handy oder Tablet den Link öffnen und über **Teilen → „Zum Home-Bildschirm“** wie eine App ablegen.

## 🛠️ Anpassen

Alles steckt in der einen Datei [`index.html`](index.html):

- **Namen der Kinder:** nach `Ilian` und `Johan` suchen und ersetzen.
- **Fußballstars:** die `<option>`-Einträge bei `star-ilian` bzw. `star-johan` ändern.
- **Textaufgaben:** in der Liste `STORIES` neue Geschichten ergänzen (Symbol + Text).
- **Reihen pro Stufe:** in der Funktion `getAllowedTables()`.
- **Anzahl der Schüsse / Tor-Ziel:** `maxTurnsVersus` (Standard 20, also 10 pro Kind) und `targetCoopGoals` (Standard 10).

## 🔗 Links

- Repository: https://github.com/michaelquehenberger/1x1
- Spiel online: https://michaelquehenberger.github.io/1x1/
- Hilfe zu GitHub Pages: https://docs.github.com/de/pages/getting-started-with-github-pages
