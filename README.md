# Ireland & Scotland — September 7–18, 2026

A phone-first trip dashboard for Leo. Open the live app:

**https://YOUR-USERNAME.github.io/ireland-scotland-2026/**

## Add it to your iPhone home screen

1. Open the link above in **Safari** (this only works in Safari, not Chrome).
2. Tap the **Share** button — the square with the arrow pointing up.
3. Scroll down and tap **Add to Home Screen**.
4. Tap **Add**.

It then behaves like an app: its own icon, full screen with no browser bars, and it
**works offline** once you've opened it — useful on the plane and anywhere data is patchy.

On Android, use Chrome's menu → *Add to Home screen*.

## What's in it

Five tabs along the bottom:

| Tab | Contents |
|---|---|
| **Trip** | Day-by-day, Sept 7–18. Confirmed items are always visible; tap *Ideas* under any day to expand suggestions for that day. |
| **Booked** | Flights, hotels, booked activities, what's still outstanding, and the not-yet-booked list in priority order. |
| **Ideas** | Reference material spanning days — the afternoon tea comparison, distilleries near the Guinness Storehouse, Edinburgh hotel logistics, and what's ruled out. |
| **Golf** | Every playable course in Cork, Edinburgh and Dublin, grouped in budget / a stretch / ruled out, with green fees, transport, club hire and phone numbers. |
| **Pubs** | Good pubs in Dublin, Cork and Edinburgh — each city leads with what's nearest the hotel, then trad sessions with nights and times, then the ones worth a walk. Includes the Dublin tourist traps to avoid and Cork stout etiquette. |
| **Info** | Rental car insurance warnings, 2026 closures, what to verify before travel, weather and packing, time zones, useful numbers. |

Phone numbers are tappable. The header shows a live countdown before the trip and
"Day *n*" once it starts.

## Editing

Everything is in `index.html` — one self-contained file, no build step and no
dependencies. Edit it, commit, and GitHub Pages redeploys in a minute or two.

If you change `index.html`, bump `CACHE` in `sw.js` (for example `trip-v1` → `trip-v2`)
so phones that already have it cached pick up the new version.
