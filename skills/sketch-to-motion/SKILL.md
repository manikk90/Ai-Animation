---
name: sketch-to-motion
description: "Your rough paper sketches turned into a polished app-promo animation: the sketch stays on the left, the finished motion graphic plays next to it, like the Kulhad chai reel. Use when the user asks for a sketch to motion graphic or types /sketch-to-motion with 8–10 photos of your sketches, plus your product photos and stock clips."
---

# Sketch to motion graphic

Your rough paper sketches turned into a polished app-promo animation: the sketch stays on the left, the finished motion graphic plays next to it, like the Kulhad chai reel.

**Input:** 8–10 photos of your sketches, plus your product photos and stock clips.
**Run it:** `/sketch-to-motion` and attach or name the file.

## Steps

1. Read each sketch: the boxes, arrows and notes like “tap!”, “zoom in + type”, “flip up”, “burst!”. Each sketch is one scene.
2. Layout: a static paper card labelled “Drawing” with the sketch, and a bigger card labelled with the Claude logo + “Opus 5.5” where the finished scene plays. Nothing spills outside the card.
3. Build each scene from real assets: real app icons, product cutouts with transparent backgrounds, stock video (rain, steam, pouring), and mood photos.
4. Do exactly what the notes say: tap with a finger and zoom, type into a search bar, flip a result screen up, scroll a photo grid, burst a word into particles.
5. Cut on the beat of the song (about every 0.55 s), and end on a logo card.
6. Render 9:16 for reels and a 16:9 version.

## Every time it runs

- Draw everything in code (an HTML canvas rendered frame by frame in headless Chrome, encoded with ffmpeg). No stock footage or image generators, so the look is the same every time.
- Time every word with forced alignment (torchaudio MMS_FA). Never guess timings.
- Show me a contact sheet of stills before the full render, and ask before overwriting files.
- Render the MP4 with the original audio, plus a 720p copy under 20 MB for WhatsApp.

---
From [aanshai.vercel.app/skills](https://aanshai.vercel.app/skills) · Animated videos
