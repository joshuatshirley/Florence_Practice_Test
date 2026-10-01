# Florence Practice ASVAB Kiosk

This is Florence's own dedicated link for the practice-ASVAB kiosk, with
Florence's individual recruiters in the dropdown instead of station names.

It shares its backend (Google Sheet, results webhook, roster dashboard)
with the [Florence_EST](https://github.com/joshuatshirley/Florence_EST)
repo, which also serves a second, separate link used as a shared tracker
across multiple stations. Results from either link land in the same Sheet.

There's nothing to deploy in this repo beyond GitHub Pages itself —
`resultsWebhookUrl` in `index.html`'s config block just
points at the Apps Script deployment that already exists. For the backend
source, the full multi-station setup process, and the station-commander
handoff guide, see `Florence_EST`'s `SETUP.md` and
`STATION_COMMANDER_GUIDE.md`.
