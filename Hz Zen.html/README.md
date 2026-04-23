# HZ-Zen -- Find Your Harmony, Every Day

A vibrant, luxury single-page web app for sound therapy and meditation. Built with a playful multi-color design system, realistic floral animations, and a complete audio engine -- all in one self-contained HTML file.

## Features

- **Binaural Beat Generator** -- Real-time Web Audio API synthesis with stereo panning, live waveform visualization, and five brain-state presets (Delta, Theta, Alpha, Beta, Gamma)
- **6 Nature Soundscapes** -- Rain, Campfire, Ocean Waves, Forest Birdsong, Thunderstorm, and Gentle Wind, each procedurally generated
- **Guided Meditations** -- Three teacher-led sessions (Breath Awareness, Body Scan, Loving-Kindness) with a circular SVG countdown timer
- **Subscription Pricing** -- Monthly and annual plans with modal checkout flow

## Design System

- **Fonts:** Outfit (display) + DM Sans (body) -- modern, playful, geometric
- **Palette:** Multi-color vibrant luxury -- teal, violet, pink, gold, and indigo accents across a deep navy base
- **Background:** Layered radial gradients with 5 morphing color blobs and prismatic crystal section dividers
- **Hero:** Realistic falling flower petals with 3-layer depth (foreground, mid, background), lateral wind sway, and natural tumble rotation
- **Logo:** Dual-orbit floral ring with breathing petal animation and transparent `mix-blend-mode: screen` treatment
- **Sections:** Alternating light/dark rhythm for visual breathing room
- **Cards:** Glass-morphism with violet-tinted borders and multi-color hover glow
- **Animations:** CSS-only -- no JavaScript animation libraries required

## Tech Stack

- HTML5 / CSS3 (custom properties, keyframe animations, backdrop-filter)
- Tailwind CSS (CDN)
- Remix Icon (CDN)
- Web Audio API (binaural beats + nature sound synthesis)
- Canvas 2D (live waveform visualization)

## File Structure

```
Hz Zen.html/
  index.html            -- Main site (current version)
  HZ-Zen.html           -- HZ-Zen Design System reference
  assets/
    hz-zen-app-icon.svg  -- App icon (SVG)
  HZ-Zen logo.png       -- Logo image
  serve.mjs             -- Local dev server (Node.js)
  screenshot.mjs        -- Puppeteer screenshot tool
  package.json          -- Dev dependencies
```

## Local Development

```bash
node serve.mjs
# Opens at http://localhost:3000
```

## License

Copyright 2025-26 NC-Developer, LLC NC-Devs. All rights reserved.
