# Bangalore Route Finder

A responsive, browser-based route finder for Bengaluru. Enter a starting place and destination to view distance and estimated travel time for:

- Walking
- Cycling
- Two-wheeler (road-route estimate)
- Car

## Live site

After enabling GitHub Pages, the site will be available at:

https://ainn5.github.io/BangaloreRouteFinder/

## Enable GitHub Pages

1. Open **Settings → Pages** in this repository.
2. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
3. Select branch **main** and folder **/(root)**, then click **Save**.
4. Wait for the Pages deployment to finish in the **Actions** tab.

## Notes

- No API key is required for the current public OpenStreetMap-based geocoding and routing services.
- Walking, cycling and road routes are calculated through public routing endpoints; service availability and rate limits may vary.
- Two-wheeler results use a road-routing estimate and are not a live-traffic motorcycle ETA.
- Google Maps links are included for turn-by-turn navigation.
- Map tiles and geocoding data are provided by OpenStreetMap contributors.
- The page is responsive and uses standard HTML, CSS and JavaScript with Leaflet.
- Page Owner: Ainn
