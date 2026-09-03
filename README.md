# MS Hwy 182 — Field Quantities Tool

Burns Dirt Construction's field quantity calculator for the MS Highway 182 Improvements
project (City of Starkville, Oktibbeha County, MS — Federal Aid No. FBLD-7113-00(004),
FMS/Con. No. 108418/801000).

## Using it

Open the live link on a phone or iPad, then add it to the home screen:

- **iPhone/iPad (Safari):** tap the Share icon → **Add to Home Screen**.
- **Android (Chrome):** tap the ⋮ menu → **Install app** (or **Add to Home screen**).

It opens full-screen like a regular app, with a Burns Dirt "BD" icon. Saved log entries are
stored locally on that device (`localStorage`) — each person's log stays on their own phone
and exports out as CSV from the Log tab.

## Updating

This is a single static page (`index.html`) plus a manifest/icons for the home-screen
install. Edit `index.html` and push to `main` — GitHub Pages redeploys automatically.
Bump `CACHE_NAME` in `sw.js` when you ship a change, so devices that already installed
it pick up the update instead of serving a stale cached copy.
