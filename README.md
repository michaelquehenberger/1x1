# ⚽ 1x1 Champions Arena

Ein Fußball-Lernspiel für das kleine Einmaleins (2. Klasse Volksschule) – für Ilian, Johan und Helena, allein oder gemeinsam.

## ▶️ Jetzt spielen

**👉 [Spiel im Browser öffnen](https://michaelquehenberger.github.io/1x1/)**

Das Spiel läuft direkt im Browser, auf PC, Tablet und Handy. Man braucht keine Installation und kein Konto.

> Der Link funktioniert, sobald GitHub Pages eingeschaltet ist (siehe [unten](#-online-stellen-github-pages)).

**Ohne Internet:** [`index.html`](index.html) herunterladen und mit Doppelklick im Browser öffnen.

## 🎮 So wird gespielt

1. **Wer spielt mit?** Ilian 🔵, Johan 🔴 und/oder Helena 🟣 mit **➕ Mitspielen** auswählen. Es können 1, 2 oder alle 3 Kinder spielen.
   - **📷 Foto:** Jedes Kind kann ein eigenes Foto auswählen. Es erscheint auf der Anzeigetafel und wenn das Kind am Ball ist.
   - **Kapitän:** Jedes Kind wählt seinen Lieblingsstar.
2. **Schwierigkeitsstufe wählen:**

   | Stufe | Einmaleins-Reihen | Freischalten |
   |---|---|---|
   | 🥉 Rookie | 1er, 2er, 5er, 10er | von Anfang an offen |
   | 🥈 Profi | 1er, 2er, 3er, 4er, 5er, 10er | 2× Rookie geschafft |
   | 🥇 Weltmeister | 2er bis 10er (alle Reihen) | 2× Profi geschafft |

   **⭐ Geschafft** = mindestens 7 von 10 Aufgaben richtig (im Team-Pokal: ca. 7 von 10 Schüssen sind Tore, also z.B. 10 Tore in höchstens 15 Versuchen).
   Jedes Kind sammelt **eigene Sterne**. Spielen mehrere Kinder zusammen, ist eine Stufe nur wählbar, wenn **alle** sie schon freigespielt haben. Gesperrte Stufen zeigen 🔒 und wie viele Sterne noch fehlen.
3. **Spielmodus wählen:**
   - 🎯 **Solo-Training** (1 Kind): 10 Schüsse – schaffst du 7?
   - ⚔️ **Elfmeter-Duell** (2–3 Kinder): Alle schießen abwechselnd, jedes Kind hat 10 Schüsse. Wer mehr Tore hat, gewinnt den Pokal.
   - 🤝 **Team-Pokal** (2–3 Kinder): Gemeinsam 5 Tore pro Kind schießen (2 Kinder = 10 Tore, 3 Kinder = 15 Tore).
4. **Aufgabenart wählen:**
   - 🔢 **Rechnen:** klassische Aufgaben wie `4 × 5 = ?`
   - 📖 **Textaufgaben:** kurze Fußball-Rechengeschichten (Sticker, Fanbus, Torwand, Pizza nach dem Sieg …). Ein **Bild mit Gruppen** zeigt die Aufgabe, z.B. 4 Kästchen mit je 5 ⚽. Mit **🔊 Vorlesen** liest der Browser die Geschichte vor. Nach der Antwort erscheint die passende Rechnung (`📝 4 × 5 = 20`).
   - 🎲 **Gemischt:** Rechenaufgaben und Textaufgaben abwechselnd.
5. **ANPFIFF!** drücken und für jede Aufgabe die richtige von 4 Antworten antippen.
   - Richtig: Der Ball fliegt ins Tor, **TOR!** ⚽, Konfetti und die Fans jubeln.
   - Falsch: Der Tormann hält 🧤, die richtige Lösung wird grün angezeigt.
6. Am Ende gibt es Sterne ⭐ und evtl. eine neu freigeschaltete Stufe 🔓. Mit **NOCHMAL!** geht es direkt weiter.

Im Hintergrund laufen Flutlicht, rollende Bälle und Fans mit La-Ola-Welle.

### 💾 Was wird gespeichert?

Sterne, Fotos und die letzte Auswahl werden **nur im Browser auf diesem Gerät** gespeichert. Die Fotos werden **nicht** hochgeladen und landen nicht auf GitHub. Auf einem anderen Gerät (oder in einem privaten Browserfenster) beginnt man wieder bei null.

### ⚙️ Eltern-Bereich

Ganz unten im Startbildschirm:
- **🔓 Alle Stufen freischalten** – z.B. wenn ein Kind schon alles kann.
- **🗑️ Fortschritt zurücksetzen** – löscht alle Sterne.

## 🌐 Online stellen (GitHub Pages)

Einmalig einrichten, damit der Link oben funktioniert:

1. Im Repository auf **Settings → Pages** gehen ([direkt hier](https://github.com/michaelquehenberger/1x1/settings/pages)).
2. Bei **Source** „Deploy from a branch“ wählen.
3. Branch **`main`** und Ordner **`/ (root)`** auswählen und auf **Save** klicken.
4. Nach 1–2 Minuten ist das Spiel unter https://michaelquehenberger.github.io/1x1/ erreichbar.

**Tipp:** Am Handy oder Tablet den Link öffnen und über **Teilen → „Zum Home-Bildschirm“** wie eine App ablegen.

## 🛠️ Anpassen

Alles steckt in der einen Datei [`index.html`](index.html):

- **Kinder, Farben & Fußballstars:** in der Liste `PLAYERS` (Name, Farbe, Kapitäne).
- **Textaufgaben:** in der Liste `STORIES` neue Geschichten ergänzen (Symbol + Text).
- **Reihen pro Stufe:** in der Funktion `getAllowedTables()`.
- **Regeln:** `WINS_TO_UNLOCK` (Sterne bis zur nächsten Stufe, Standard 2), `PASS_CORRECT` (richtige Antworten für einen Stern, Standard 7), `SHOTS_PER_PLAYER` (Standard 10), `COOP_GOALS_PER_PLAYER` (Standard 5).

## 🔗 Links

- Repository: https://github.com/michaelquehenberger/1x1
- Spiel online: https://michaelquehenberger.github.io/1x1/
- Hilfe zu GitHub Pages: https://docs.github.com/de/pages/getting-started-with-github-pages
