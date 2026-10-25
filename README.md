# Geheime Geburtstagsmission 🎁

Ein Geburtstagsrätsel auf einer einzigen HTML-Seite. Es sieht aus wie ein lustiges Quiz, verteilt aber bei jeder Antwort heimlich Punkte auf vier Geschenke:

- ✒️ Tattoo
- 🌴 Urlaub auf Mallorca
- 🚗 Auto
- 💇 Typveränderung (Haarschnitt + neue Klamotten)

Am Ende gibt es ein „Goldenes Ticket“ für das Geschenk mit den meisten Punkten. Bei Gleichstand entscheidet eine Stichfrage.

## Anpassen

Alles Wichtige steht oben im `<script>`-Block von `index.html` unter **HIER ANPASSEN**:

- `CONFIG.name`: Name deines Bruders
- `CONFIG.from`: Dein Name
- `GIFTS`: Titel und Text der Gutscheine
- `QUESTIONS`: Fragen und die geheimen Punkte pro Antwort

## Ergebnis erfahren (ohne Server)

- Er macht einen Screenshot vom Ticket oder schickt es dir über den WhatsApp-Button.
- Das Ergebnis wird im Browser gespeichert. Lädt er die Seite neu, sieht er wieder sein Ticket und kann nicht neu würfeln.
- Zum Testen: `index.html?reset` an die Adresse hängen, dann startet das Quiz neu.

## Auf GitHub Pages veröffentlichen

1. `index.html` muss auf dem Branch `main` liegen.
2. Im Repo: **Settings → Pages → Build and deployment → Deploy from a branch**, Branch `main`, Ordner `/ (root)`.
3. Nach ca. 1 Minute ist die Seite unter `https://<benutzername>.github.io/<repo-name>/` erreichbar.
