# Kellner — GitHub Pages

Statische Seiten für Apple App Store / TestFlight (Datenschutz, Support, Impressum). Dieser Ordner ist die Pages-Wurzel: nur den **Inhalt** von `website/` veröffentlichen, nicht den ganzen App-Quellcode.

Es gibt keine JavaScript-Abhängigkeit. Keine `CNAME`-Datei — erst anlegen, wenn eine eigene Domain feststeht.

## Veröffentlichen

1. Auf GitHub ein **öffentliches** Repository anlegen (leer, ohne README, wenn Sie die Dateien selbst hochladen).
2. Den **Inhalt** dieses Ordners `website/` ins Repository legen:
   - **Variante A — Repo-Wurzel:** `index.html`, `datenschutz.html`, `styles.css`, … liegen direkt im Root des Repos.
   - **Variante B — `/docs`:** dieselben Dateien in einen Ordner `docs/` im Repo legen (nicht den übergeordneten App-Quellcode).
3. Im Repo: **Settings → Pages**.
4. **Build and deployment:** Source **Deploy from a branch**.
5. Branch wählen (meist `main`) und Ordner **`/` (root)** für Variante A oder **`/docs`** für Variante B. Speichern.
6. Nach ein bis zwei Minuten ist die Seite erreichbar unter:

   `https://<github-user>.github.io/<repo>/`

   Beispiel: Nutzer `kaltenkirchener`, Repo `kellner-pages` → `https://kaltenkirchener.github.io/kellner-pages/`

   (Bei einem User-/Org-Repo namens `<github-user>.github.io` entfällt der Repo-Teil: `https://<github-user>.github.io/`.)

## Nach dem Deploy

Die öffentlichen URLs für die iOS-App stehen in [URLS.md](URLS.md). Impressum-Platzhalter (`REPLACE-ME`) durch echte Anschrift und Vertretung ersetzen.

Support-E-Mail auf den Seiten: `support@kaltenkirchener-steakhouse.com` (kann der Betrieb später ändern).
