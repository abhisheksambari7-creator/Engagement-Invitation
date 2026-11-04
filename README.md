# Manchikatla Family — Engagement Invitation

A responsive, mobile-first, static wedding engagement invitation inspired by an interactive envelope reveal, with South Indian motifs and matte frosted-glass styling.

## Edit before publishing
1. Open `config.js` and set `eventDate` in `YYYY-MM-DD` format. The site deliberately shows **Date to be announced** until set.
2. Confirm the official venue name and map destination. The current map button uses a Google Maps text search, not a verified map pin.
3. Confirm the spelling of the couple's names and venue, contact numbers, and exact lunch wording.
4. Optionally add an MP3 you have the rights to use and set `musicFile: 'assets/music.mp3'` in `config.js`. Audio starts only after a user clicks the music control.
5. Preview `index.html` locally, or use a local server (`python -m http.server 8000`).

## Publish to GitHub Pages
1. Create a public repository, e.g. `manchikatla-engagement`.
2. Upload `index.html`, `style.css`, `script.js`, `config.js` and this README to the root of the `main` branch.
3. In repository **Settings → Pages**, choose **Deploy from a branch**, select **main** and **/(root)**, and save.
4. Your invitation will appear at `https://YOUR_USERNAME.github.io/manchikatla-engagement/` after deployment.

No build tools, frameworks, API keys, tracking, or server required. The Google Fonts import requires internet access; local fallback fonts work offline. The RSVP button opens WhatsApp to the first listed number and does not automatically send a message.


## Confirmed event date and theme
- **Sunday, 15 November 2026**, engagement at **10:00 AM**, lunch to follow.
- Regal burgundy / champagne gold with translucent, glossy, blurred glass cards.
- The uploaded couple photograph is at `assets/maitri-dinesh.jpg`.
- Please verify venue spelling and address with the family before publishing.
