# Tonio Armani Travel Planner Starter App

This is a working Next.js starter app for your tour travel workflow.

## What it already does
- Add a single show
- Bulk import multiple shows
- Automatically routes flights from the previous show when the gap is 2 days or less
- Resets the flight origin to RDU when the gap is larger than 2 days
- Lets you change status for each show
- Stores data in your browser with local storage
- Exports a CSV master sheet
- Prints or saves the itinerary view as PDF

## How to run it
1. Install Node.js LTS from https://nodejs.org
2. Open a terminal in this folder
3. Run:

```bash
npm install
npm run dev
```

4. Open http://localhost:3000

## How to deploy to Vercel
1. Create a GitHub repo and upload this folder
2. Go to https://vercel.com
3. Import the GitHub repo
4. Click Deploy

## Bulk import format
Paste one show per line like this:

```text
Apr 10 2026 — Nashville — TBD — 7:00 PM
Apr 11 2026 — Arlington — College Park Center — TBD
May 1 2026 — Gretna — Springfield Multipurpose Center — TBD
```

## Next upgrades
- Replace sample flight cards with live flight API results
- Replace sample hotel cards with live hotel results
- Add Supabase so the data is shared across devices and users
- Add login and a shareable public itinerary page
