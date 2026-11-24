# First Blood — Dynamic Scenario Generator

**A Fan-made Community Project by BlazerVX · Version 1.0**

A phone-first web app for **Conquest: First Blood** that walks two players through the official Dynamic Scenarios process (First Player roll-off, drafting, Tactics, deployment), shows the battlefield maps, tracks Victory Points round by round, rolls Supremacy and prints an end-of-battle results summary ready to paste into an event form.

Unofficial. Not a Para Bellum product. Conquest, its art and its rules are © Para Bellum Wargames, used with their permission as community content. No Para Bellum logos are used.

Inspired by PTWookie's First Blood scenario generator, shared in the community Discord.

## Use it

Open the app: **https://blazervx.github.io/fb-scenario-generator/**

### Install it on your phone

- **iPhone / iPad (Safari):** open the link, tap **Share → Add to Home Screen**.
- **Android (Chrome):** open the link, tap **⋮ → Install app** (or *Add to Home screen*).
- **Desktop (Chrome / Edge):** click the install icon in the address bar.

After the first visit it works **fully offline** (handy in a game store with no signal). Open it once while online so the fonts get cached too.

Games save on your device only. Nothing is sent anywhere.

The app icon is an Old Dominion miniature from Para Bellum, painted by BlazerVX.

## What's inside

| File | What it does |
|---|---|
| `index.html` | The whole app (rules data, maps and art are embedded) |
| `manifest.webmanifest` | Makes it installable (name, icon, colours) |
| `sw.js` | Service worker: offline support and updates |
| `icons/` | Home-screen icons (BlazerVX's painted Old Dominion skull) |
| `.nojekyll` | Tells GitHub Pages to serve the files as-is |

## Updating

1. Replace `index.html` with the new version.
2. In `sw.js`, bump `VERSION` (e.g. `fbgen-v1.0.1`).
3. Commit. Installed copies pick up the update the next time they open online.

## Credits

- App design and code: **BlazerVX** (Para Bellum Vanguard)
- Inspired by **PTWookie**'s original First Blood scenario generator
- Scenario rules, maps and artwork: © Para Bellum Wargames, used with permission as fan-made community content
