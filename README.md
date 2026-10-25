# airport-run
Airport pickup & drop planner for UAE airports (DXB, SHJ, AUH, DWC)

## What it does
- Type the flight number: airport, terminal, time and pickup/drop fill in by themselves
- Big **Leave by** time for the next trip, with a clear timeline: Leave → Collect → At airport → Flight
- Drops collect the passenger from their saved place on the way
- Drive times from a free map (plus 15%, and 20 min more in weekday rush hour)
- Live flight status, delays and baggage belt via AeroDataBox; trips move to History by themselves
- Track any flight or browse an airport board, without making a trip
- History with monthly report (share or CSV), backup and restore
- Everything is saved on the phone only. Nothing is stored in this repo.

## Publish (GitHub Pages)
1. Upload `index.html` and `README.md` to this repo
2. **Settings → Pages → Source: Deploy from a branch → `main` / root → Save**
3. Link after a minute or two: `https://nameerhameed.github.io/airport-run/`

## Install on iPhone
1. Open the link in **Safari**
2. Tap **Share → Add to Home Screen → Add**
3. Open it from the home screen icon (trips are saved in that copy)

## Maps (free, no key)
Places are picked on OpenStreetMap (search, tap to drop a pin, or use current location).
Drive times come from the free OSRM router plus 15%, with 20 min extra in weekday rush hour.
"Traffic now" still opens Google Maps for live traffic.

## Live flight data key (free)
1. Sign up at **rapidapi.com**
2. Search **AeroDataBox** → **Pricing** → subscribe to the free **Basic** plan
3. Open **Endpoints**, copy the value of **X-RapidAPI-Key**
4. In the app: **Settings → Flight data** → paste → **Save key** (or paste it in the first-run setup)

The key stays on the phone. Never put it in this repo, it's public.
The app checks flights only within 12 hours of the flight, every 10 minutes while open, to stay inside the free monthly limit.
