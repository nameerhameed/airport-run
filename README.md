# airport-run
Airport pickup & drop planner for UAE airports (DXB, SHJ, AUH, DWC)

## What it does
- Add a pickup or drop with flight number, date, time, airport and terminal
- Shows a big **Leave by** time with a countdown, based on drive time and traffic
- Live flight status (delay, landing time, terminal, gate, belt) via AeroDataBox
- One-tap Flightradar24, Google flight status and Google Maps traffic
- Trip history with monthly pickup/drop counts
- Everything is saved on the phone only. Nothing is stored in this repo.

## Publish (GitHub Pages)
1. Upload `index.html` and `README.md` to this repo
2. **Settings → Pages → Source: Deploy from a branch → `main` / root → Save**
3. Link after a minute or two: `https://nameerhameed.github.io/airport-run/`

## Install on iPhone
1. Open the link in **Safari**
2. Tap **Share → Add to Home Screen → Add**
3. Open it from the home screen icon (trips are saved in that copy)

## Live flight data key (free)
1. Sign up at **rapidapi.com**
2. Search **AeroDataBox** → **Pricing** → subscribe to the free **Basic** plan
3. Open **Endpoints**, copy the value of **X-RapidAPI-Key**
4. In the app: **Setup → Live flight updates** → paste → **Save key**

The key stays on the phone. Never put it in this repo, it's public.
The app checks flights only within 12 hours of the flight, every 10 minutes while open, to stay inside the free monthly limit.
