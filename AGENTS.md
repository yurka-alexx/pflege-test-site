# AGENTS.md: pflege-test-site

Testseite für die Abnahme der Website-Pflege per Sprache (AK3). Nur Beispieltext, keine echten Kundendaten.

## Zugangsweg

GitHub-Repo `yurka-alexx/pflege-test-site`, Branch `main`. Zugriff per git über SSH mit dem Agent-Key des Mini.

## Build

Keiner. Die Seite ist statisch, die Dateien liegen fertig in `public/`.

## Deploy

Push auf `main`. Der GitHub-Actions-Lauf „Pages“ veröffentlicht `public/` über GitHub Pages unter https://repo.pflege-test.able-baker.de/. Der Deploy ist fertig, wenn der Lauf grün ist.

## Erlaubte Pfade

- `public/` (der änderbare Text steht in `public/index.html`)

## Verbote

- Nichts außerhalb von `public/` ändern, vor allem nicht diese `AGENTS.md` und nicht `.github/`.
- Keine Dateien löschen, keine Abhängigkeiten hinzufügen, kein Force-Push.

## CMS

Nein.
