# AGENTS.md: Testkunde Musterbäckerei (Repo-Weg)

Testwebsite der Able & Baker GmbH für den Änderungsdienst „Website-Pflege per Sprache“. Keine echte Firma, keine echten Daten. SOP: `Able & Baker/Agenturexpertise/Webdesign/SOP/agents-md-kundenwebsite.md`.

## Website
- Live-URL: https://pflege-test.able-baker.de/repo/
- Stack: statisches HTML, kein Build, kein CMS
- Quelltext: Repo `yurka-alexx/pflege-test-site`, Branch `main`

## Änderungen einspielen
- Weg: Repo. Änderung auf `main` committen und pushen, danach die geänderten Dateien per FTPS nach `/pflege-test.able-baker.de/httpdocs/repo/` hochladen (Host `ae99f.netcup.net`, Benutzer `cleo-ftp`, Keychain `ops/ftp-cleo`). Ohne Upload ist nichts live. `AGENTS.md` und `README.md` werden nicht hochgeladen.
- Nach jeder Änderung: nichts weiter zu tun (kein Build, kein Cache).
- Prüfung danach: Live-URL aufrufen, Status 200, geänderter Text sichtbar. Inhalte haben feste IDs (`telefon`, `zeit-wochentags`, `aktuelles-text`, `angebot-liste` usw.).

## Grenzen
- Nicht anfassen: `AGENTS.md`, `impressum.html`, `.github/`.
- Nur Deutsch, keine weiteren Sprachen.
- Bilder: nach `bilder/`, WebP, höchstens 1600 px Breite, unter 300 KB.

## Kontakt
- Freigabe: Yuri (intern), Ansprechpartner Davit
- Zugangsdaten: keine nötig außer dem GitHub-Token des Mini (Keychain `ops/github-pat`)
