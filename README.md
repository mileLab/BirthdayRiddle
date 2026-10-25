# Geheime Geburtstagsmission 🎁

Ein Geburtstagsrätsel im Joker-Stil auf einer einzigen HTML-Seite. Der Joker hat das Geschenk versteckt und spielt ein Spiel: Karten ziehen, aus Arkham ausbrechen, ein echtes Rätsel, Münzwurf, ein falsches Zwischenergebnis und am Ende ein gezinktes Kartenspiel. Hinter den Kulissen verteilt jede Antwort heimlich Punkte auf vier Geschenke:

- ✒️ 300 € Tattoo-Gutschein
- 🌴 Gutschein für Urlaub auf Mallorca (Flug + Organisation)
- 🚗 500 € Zuschuss fürs Auto
- 💇 300 € für eine Typveränderung (Haarschnitt + neue Klamotten)

Die Antworten verraten das Geschenk nicht direkt: Fast jede Antwort zählt für zwei Geschenke, und die Chaos-Runden zählen gar nicht. Am Ende zieht er eine von vier verdeckten Karten. Egal welche, sie zeigt immer das Geschenk mit den meisten Punkten (der Joker schummelt). Danach gibt es die „Joker-Karte“ als Gutschein. Bei Gleichstand entscheidet eine Stichfrage.

## Anpassen

Alles Wichtige steht oben im `<script>`-Block von `index.html` unter **HIER ANPASSEN**:

- `CONFIG.name`: Name deines Bruders
- `CONFIG.from`: Dein Name
- `GIFTS`: Titel und Text der Gutscheine
- `QUESTIONS`: Fragen und die geheimen Punkte pro Antwort, dazu das Rätsel (`type: "riddle"`), die Chaos-Runden (`type: "chaos"`) und das falsche Zwischenergebnis (`type: "fakeout"`)

## Ergebnis erfahren (ohne Server)

- Er macht einen Screenshot vom Ticket oder schickt es dir über den WhatsApp-Button.
- Das Ergebnis wird im Browser gespeichert. Lädt er die Seite neu, sieht er wieder sein Ticket und kann nicht neu würfeln.
- Neu starten: unten auf der Ergebnisseite auf „Spiel zurücksetzen“ tippen (mit Nachfrage), oder `?reset` an die Adresse hängen.

## Auf GitHub Pages veröffentlichen

1. `index.html` muss auf dem Branch `main` liegen.
2. Im Repo: **Settings → Pages → Build and deployment → Deploy from a branch**, Branch `main`, Ordner `/ (root)`.
3. Nach ca. 1 Minute ist die Seite unter `https://<benutzername>.github.io/<repo-name>/` erreichbar.
