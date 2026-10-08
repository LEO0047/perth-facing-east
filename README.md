# Facing East

A Perth sunset you scroll through, watched the local way: from Kings Park with the sun behind you. Scroll down and the clock moves forward. The city is lit head-on, then the shadow of Kings Park climbs the towers, the Earth's shadow rises over the Darling Scarp with the pink Belt of Venus above it, and the city's lights take over.

## What's real

- **The sun.** Its position, tonight's sunset time and the twilight times are calculated in the browser for Perth's current date (NOAA solar position algorithm).
- **The shadows.** When each part of each tower drops into shadow comes from the sun's height and the hill you are standing on. The centre of the Earth's shadow is placed opposite the sun, at its real bearing.
- **The view.** Central Park, Brookfield Place, 108 St Georges Terrace, the Bell Tower, Optus Stadium, Matagarup Bridge and Crown sit at their real bearings and distances from the State War Memorial in Kings Park.
- **The lights.** Optus Stadium's roof halo (more than 15,000 LEDs), the LED arches of Matagarup Bridge and the lit spire of the Bell Tower.

## What's stylized

Heights are slightly stretched. The shoreline of Perth Water is traced from the map by hand. Smaller buildings, the suburbs, trees, clouds and water are generated.

## Run it

It is a single `index.html` with no build step. Open it in a browser, or serve the folder with any static server. Fonts load from Google Fonts. It needs a browser with WebGL 2 and falls back to a still image without it. Motion is reduced when the system asks for reduced motion.
