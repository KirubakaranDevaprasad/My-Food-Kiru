# Kiru's Food App 🥟🍜🍣

A personal food finder for eating solo, wherever I am. It surfaces Chinese, Vietnamese and Japanese spots near my live location, plus new openings, budget picks, farm-to-table kitchens, and dishes I haven't tried yet. It learns from every 😋 and 🙅.

## Features
- **Live location, follow mode:** finds spots around you and refreshes as you travel
- **Real spots anywhere:** pulled from OpenStreetMap (Overpass, with mirror failover), plus a researched starter list around Parsippany and Morristown
- **Drive and walk times:** OSRM routing, one-tap Google Maps directions
- **"What are you doing?" modes:** Solo & on the go · Working · Quick bite · Treat myself · Late night · Exploring
- **Filters:** veg / non-veg / both · budget $–$$$ · cuisine · radius
- **Search with auto-suggest:** dishes, cuisines, moods, spots and flavors ("spicy", "soup", "tea"), keyboard friendly
- **Rails:** auto-scrolling *Flavors to try next*, *Closest to you*, *New, cheap & cheerful*, *Farm-to-table & veg-forward*, *Sips & sweets*
- **🎲 Surprise me:** a weighted spin picks a dish you'll likely love, plus a nearby spot that serves it
- **Taste DNA:** cuisine leanings, favourite flavors, and a history of likes and modes. It drives every match score.

## Tech
Static HTML/CSS/JS on GitHub Pages. Free, keyless APIs: OpenStreetMap Overpass, Nominatim, OSRM, Wikipedia (dish photos), and the browser Geolocation API. Preferences stay in `localStorage`.
