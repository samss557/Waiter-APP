# URLs für die iOS-App

Nach dem GitHub-Pages-Deploy die Basis-URL voranstellen:

`https://<github-user>.github.io/<repo>/`

Pfade, die die App öffnen soll:

| Zweck | Pfad |
|---|---|
| Privacy | `datenschutz.html` |
| Support | `support.html` |

Vollständig:

- Privacy: `https://<github-user>.github.io/<repo>/datenschutz.html`
- Support: `https://<github-user>.github.io/<repo>/support.html`

Diese Werte in `src/config/legal.ts` eintragen (`PRIVACY_POLICY_URL`, `SUPPORT_URL`), sobald die Pages-URL feststeht.
