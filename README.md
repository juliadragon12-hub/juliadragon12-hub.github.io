# Julia Drake — Digital Business Card

Tap-to-share business card for Julia Drake / Julia Drake Photography.

- **Live card:** https://juliadragon12-hub.github.io/
- **Edit the card:** https://juliadragon12-hub.github.io/edit.html

## How it works

The Android app ("My Card", package `com.juliadrake.cardapp`) emulates an
NFC Forum Type 4 tag carrying this page's URL, only while the app is open
in the foreground. A phone tapped against it opens this page in its
browser — no app needed on the receiving side. The app also shows a QR
code for the same URL.

## Customizing

Everything on the card — name, title, tagline, buttons and their order,
colors, and whether the Resume button shows — lives in `config.json`.
The page reads it fresh on every load, so edits apply without an app
update and the URL never changes. Use the editor page, edit
`config.json` here on GitHub, or ask Luc in the Muse app.

## Files

- `index.html` — the card page
- `edit.html` — the card editor
- `config.json` — the card's content and settings
- `resume.pdf` — Julia's resume (the Resume button links here, and only
  shows when `showResume` is true in `config.json`; the file itself is
  public at its direct address whenever it is in this repo)
