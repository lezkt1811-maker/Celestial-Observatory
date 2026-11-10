# Celestial Observatory

A standalone 3D true-sky 13-sign birth chart by [StarChart13](https://starchart13.com).

Enter a birth date, time and city, then step inside your birth sky: a holographic wheel
floating over an astronomical control table, with all 13 zodiac constellations
(Ophiuchus included, real unequal IAU boundaries), 13 unequal houses from the Ascendant,
and four live panels: Orbital Mechanics, Planetary Positions, Constellation Tracking
and Astronomical Events.

- `index.html`: birth form + the StarChart13 chart engine (copied unchanged)
- `observatory.js`: the 3D observatory (Three.js, loaded only when opened)
- `ecliptic-view.js`: real star-line coordinates for the constellation figures
- `tropical.js`: tropical sign shown only as a labelled reference

Everything runs in the browser. No accounts, no paid APIs. Works on Android and desktop,
with a 2D fallback when 3D (WebGL) isn't available.

Publish with GitHub Pages: Settings → Pages → Deploy from branch → `main` / root.
