---
name: news-report
description: "A Hinglish tech-news report in Fireship style: flat dark background, screenshot cards with red boxes and highlights, memes, and a hard cut every two seconds, with you as the anchor. Use when the user asks for a tech news report or types /news-report with a news topic or 2–3 article links."
---

# Tech news report

A Hinglish tech-news report in Fireship style: flat dark background, screenshot cards with red boxes and highlights, memes, and a hard cut every two seconds, with you as the anchor.

**Input:** a news topic or 2–3 article links.
**Run it:** `/news-report` and attach or name the file.

## Steps

1. Read the links, fact-check every claim, and write a 60-second Hinglish script: a BREAKING cold open, 2–3 stories, and a comment-keyword CTA. Give it to me ready for ElevenLabs v3 (Hindi in Devanagari, brand names in English, [tone] tags).
2. When I send the voice MP3, force-align it and plan a hard cut every 1.5–3 seconds.
3. Recreate each source as a flat card (release notes, pricing table, leaderboard, tweet) on #242021, with a thin red box and an orange highlighter on the key line, then a zoom-in.
4. In the 9:16 version, put my face cutout at the bottom, changing expression with the tone of each line.
5. Add sound effects on the same cues (whoosh on cuts, ding on numbers, a sting on BREAKING) and credit every source on screen.
6. Render 9:16 and 16:9.

## Every time it runs

- Draw everything in code (an HTML canvas rendered frame by frame in headless Chrome, encoded with ffmpeg). No stock footage or image generators, so the look is the same every time.
- Time every word with forced alignment (torchaudio MMS_FA). Never guess timings.
- Show me a contact sheet of stills before the full render, and ask before overwriting files.
- Render the MP4 with the original audio, plus a 720p copy under 20 MB for WhatsApp.

---
From [aanshai.vercel.app/skills](https://aanshai.vercel.app/skills) · Animated videos
