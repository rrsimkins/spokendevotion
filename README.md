# Spoken Devotion

**Words that heal, lift, and draw us closer to God.**

A ministry of spoken poetry, worship, prayer, and Scripture — focused on emotional strength and honoring Christ and God the Father.

## Our Mission

To create content that strengthens the heart, comforts the soul, and glorifies our Lord Jesus Christ. Through spoken words, we seek to provide emotional healing, spiritual encouragement, and a deeper connection with God the Father and His Son.

## Live Site

→ [spokendevotion.com](https://spokendevotion.com/)

**DNS note:** For `www.spokendevotion.com` to work, add a CNAME record at your domain registrar pointing `www` to `awsimkins.github.io`. The apex domain (`spokendevotion.com`) is configured via the repo `CNAME` file.

## Current Site Sections

| Section       | Description                                      | Link |
|---------------|--------------------------------------------------|------|
| **Home**      | Featured content, mission, and quick access to audio | [Home](https://spokendevotion.com/) |
| **Worship**   | Original worship songs with lyrics in modal      | [Worship](https://spokendevotion.com/worship/) |
| **Prayer**    | Written & spoken prayers with full text modals   | [Prayer](https://spokendevotion.com/prayer/) |
| **Confessions** | Poetic reflections and honest spoken-word pieces | [Confessions](https://spokendevotion.com/confessions/) |
| **Bible**     | Spoken Devotion Version (SDV) — full book list with James via YouTube embed | [Bible](https://spokendevotion.com/bible/) |
| **Instrumental** | Quiet instrumental tracks for prayer and reflection | [Instrumental](https://spokendevotion.com/instrumental/) |
| **Contact**     | Contact form via Web3Forms (add access key in config)  | [Contact](https://spokendevotion.com/contact/) |

## Key Features

- **Playable audio** directly on the homepage featured sections
- **Share buttons** — one-click copy of direct audio links
- **Modals** for full lyrics, poetry, and prayer text (keeps pages clean)
- **Book of James** available via YouTube video embed in the Bible section
- Clean, responsive design built with Tailwind CSS
- Shared navigation and footer loaded from `partials/`
- Content managed via JSON files for easy updates (`lyrics.json`, `confessions.json`, `prayer.json`)

## Platforms

Active on:
- [YouTube](https://www.youtube.com/@Spoken_Devotion)
- [Instagram](https://www.instagram.com/spoken_devotion/)
- [Facebook](https://www.facebook.com/profile.php?id=61591326358064)

Coming soon (God willing):
- TikTok
- X (Twitter)
- Spotify
- Apple Music
- Other streaming platforms

## Contact

Use the [Contact Us](https://spokendevotion.com/contact/) page. Form submissions go through [Web3Forms](https://web3forms.com/) — set your access key in `partials/contact-config.js` and configure `contact@spokendevotion.com` as the notification email in the Web3Forms dashboard.

## Still To Do

See also [`DEFERRED.md`](DEFERRED.md) for the full backlog. Priority items for the next session:

- [ ] **Web3Forms access key** — replace `YOUR_WEB3FORMS_ACCESS_KEY` in `partials/contact-config.js`; set notification email to `contact@spokendevotion.com` and enable autoresponder in dashboard
- [ ] **TikTok & X links** — add profile URLs when accounts are ready (homepage shows Coming Soon badges for now)
- [ ] **Instrumental tracks** — add audio files and cards on `/instrumental/` when ready
- [ ] **YouTube migration** — move hosted MP3s to YouTube embeds instead of serving files from the repo

- [ ] **Page banners** — add remaining banner images (`worship.png`, `prayer.png`, `confessions.png`, `bible.png`, `instrumental.png`) under `/images/`

## Vision

To create content that strengthens the heart, comforts the soul, and glorifies our Lord Jesus Christ through the power of spoken words.

---

© 2026 Spoken Devotion • All glory to God the Father

*Spoken Devotion is part of the Simkins family ministries, alongside KanoJoes — wholesome family content for all ages.*