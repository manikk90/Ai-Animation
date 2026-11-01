---
name: watercolor-map
description: "A painted watercolor world map: a pin drops on the start city, a plane flies the real great-circle route, and the destination washes in with colour. Use when the user asks for a watercolor map journey or types /watercolor-map with two places, like “Bengaluru → California”."
---

# Watercolor map journey

A painted watercolor world map: a pin drops on the start city, a plane flies the real great-circle route, and the destination washes in with colour.

**Input:** two places, like “Bengaluru → California”.
**Run it:** `/watercolor-map` and attach or name the file.

## Steps

1. Set up a Remotion project with d3-geo, topojson-client and world-atlas.
2. Fit a map projection around the route and paint every country as an uneven watercolor wash using SVG turbulence, displacement and edge-pooling filters, with paper grain on top.
3. Draw the great-circle route with d3's geoInterpolate and fly a small plane along it, turned to its heading, leaving a dashed red trail.
4. Camera: start close on the first city, zoom out to follow the plane, then zoom into the destination.
5. Add handwritten labels for both places, a running km counter, and an end title card.

## Every time it runs

- Build it in Remotion. Animate only with useCurrentFrame() and interpolate(), never CSS animations.
- Use real map data (world-atlas) and the real great-circle route, never a hand-drawn line.
- Show me 5 stills across the video before the full render.
- Render 1920×1080 at 30 fps, and a 1080×1920 version if I ask.

---
From [aanshai.vercel.app/skills](https://aanshai.vercel.app/skills) · Animated videos
