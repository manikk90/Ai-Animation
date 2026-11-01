---
name: podcast-explainer
description: "A podcast clip turned into an animated explainer, like the Raj Shamani “Two Winners” video: simple stick-figure metaphors for every idea, bold kinetic captions, and the host drawn as a cartoon in a live corner window. Use when the user asks for a podcast explainer or types /podcast-explainer with a 45–90 second podcast clip (MP3)."
---

# Podcast explainer

A podcast clip turned into an animated explainer, like the Raj Shamani “Two Winners” video: simple stick-figure metaphors for every idea, bold kinetic captions, and the host drawn as a cartoon in a live corner window.

**Input:** a 45–90 second podcast clip (MP3).
**Run it:** `/podcast-explainer` and attach or name the file.

## Steps

1. Transcribe the clip and force-align every word. Split it into 6–10 ideas and give each one a short chapter chip (01 NO BACKUP, 02 NO PLAN B…).
2. For each idea, design one simple visual metaphor on a warm off-white background: a tightrope with no safety net, a crossed-out word, a line chart that turns around, two figures compared side by side.
3. Draw the host as a flat cartoon (same face, beard and outfit every time), lip-synced to the voice, sitting in a small LIVE window in the top corner. Open and close on a big shot of him at his desk.
4. Captions: 3–4 words, bold condensed caps, the spoken word in yellow and key words in a red pill.
5. End on a big quote card with the main line and the podcast's credit.
6. Render 16:9, plus a 9:16 version with the visuals in the top half and the host below.

## Every time it runs

- Draw everything in code (an HTML canvas rendered frame by frame in headless Chrome, encoded with ffmpeg). No stock footage or image generators, so the look is the same every time.
- Time every word with forced alignment (torchaudio MMS_FA). Never guess timings.
- Show me a contact sheet of stills before the full render, and ask before overwriting files.
- Render the MP4 with the original audio, plus a 720p copy under 20 MB for WhatsApp.

---
From [aanshai.vercel.app/skills](https://aanshai.vercel.app/skills) · Animated videos
