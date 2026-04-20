# Savour TO

A personal food journal for tracking restaurant and café visits across Toronto.

## Features

- **Map** — real Toronto map (OpenStreetMap) with venue pins, colour-coded by type. Click any pin to see details.
- **Genres** — browse venues by cuisine (Japanese, Café, Mediterranean, French, Mexican, Thai, Italian, Brunch, Korean, Indian) with a progress bar showing how many you've visited.
- **My journal** — chronological feed of all your visit notes.
- **Record a visit** — star rating + notes saved to your journal. Marks the venue as visited on the map.
- **Add a venue** — type any Toronto address and it geocodes the pin automatically.
- **Mobile layout** — bottom nav and slide-up sheet for the venue list.

All data is saved locally in your browser (localStorage) — nothing is sent to a server.

## Usage

Open [https://alanjunzhu.github.io/savour-to](https://alanjunzhu.github.io/savour-to) in any browser.

No install, no login, no build step.

## Stack

- React 18 (via CDN, no build tooling)
- Leaflet.js + OpenStreetMap tiles
- Nominatim for address geocoding
- Playfair Display + DM Sans (Google Fonts)
