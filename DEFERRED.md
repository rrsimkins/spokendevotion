# Deferred Items

Items intentionally held for later — not forgotten.

## Prayers to the Father — Streaming
Album uploaded to DistroKid. Pre-sales are open now; full release **July 3, 2026** on Spotify, Apple Music, and other platforms. Pre-save: [distrokid.com/hyperfollow/spokendevotion/prayers-to-the-father](https://distrokid.com/hyperfollow/spokendevotion/prayers-to-the-father). After release, replace homepage Spotify / Apple Music / YouTube Music “Coming soon” cards with live profile links.

## Alone in an Empty Grave — Single
Uploaded to DistroKid for **July 3, 2026** release. Pre-save: [distrokid.com/hyperfollow/spokendevotion/alone-in-an-empty-grave](https://distrokid.com/hyperfollow/spokendevotion/alone-in-an-empty-grave). Add streaming player to `/reflections/` when live.

## Formspark Contact Form
Contact form uses Formspark + Cloudflare Turnstile. Form ID and Turnstile site key are in `partials/contact-config.js`. Turnstile **secret key** lives only in the Formspark dashboard. Notification email: `contact@spokendevotion.com`.

## Reflections Section
`/reflections/` lists **Alone in an Empty Grave** and **Lost** (both pre-save live; streaming players after July 3, 2026). Pre-save: [alone-in-an-empty-grave](https://distrokid.com/hyperfollow/spokendevotion/alone-in-an-empty-grave), [lost](https://distrokid.com/hyperfollow/spokendevotion/lost). Lyrics in `reflections/reflections.json`.

## Worship Singles
**Have Mercy on Me** and **Here I Am, Lord** uploaded to DistroKid for **July 3, 2026** release. Pre-sales open now. Pre-save: [have-mercy-on-me](https://distrokid.com/hyperfollow/spokendevotion/have-mercy-on-me), [here-i-am-lord](https://distrokid.com/hyperfollow/spokendevotion/here-i-am-lord). Credits: lyrics by Anthony, produced and sang by Suno. Add streaming players to `/worship/` when live. Lyrics in `worship/lyrics.json`.

## Instrumental Tracks
Instrumental page is live in navigation (Soon badge) with a coming-soon message. Add real tracks when audio files are ready.

## YouTube Migration for Audio
Prayer section complete — Prayer for Family, Prayer of Repentance, and Prayer of Need use YouTube embeds. Worship singles are on DistroKid pre-save (MP3 previews removed from `/worship/` until streaming goes live). Confessions still use hosted MP3s where applicable.

## Banner Image Optimization
All section banners are in place (`main`, `bible`, `confession`, `instrumental`, `prayer`, `reflections`, `worship`). Optional: compress large PNGs (e.g. `instrumental.png`, `worship.png`) for faster loads.