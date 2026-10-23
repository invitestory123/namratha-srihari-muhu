# Customer Editing Guide — Namratha & Srihari Wedding Invitation

This template is an illustrated wedding invitation for Namratha & Srihari featuring a tap-to-open video opener gate, illustrated couple hero cover card, custom monogram, background music player, parents blessing card, celebration events (Wedding Muhurtham), interactive lantern-wish animation, venue map, and family compliments.

---

## Normal Customer Changes

All routine customer edits are configured in:
→ `editable/wedding-data.js`

### Couple & Parents Names
Edit `couple` in `editable/wedding-data.js`:
- `bride`: "Namratha"
- `groom`: "Srihari"
- `brideParents`: "A Sandhya Prasad & R Venkatesh Prasad"
- `groomParents`: "Sumana T & Surendranath W"
- `compliments`: "Amrutha V"
- `family`: ["Amith & Rohith", "Srinidhi & Soumya", "Prathik & Aishwarya"]

### Wedding Date & Timeline Events
Edit `wedding`, `events`, and `eventDates` in `editable/wedding-data.js`:
- `dateLabel`: "26 November 2026"
- `weddingISO`: "2026-11-26T09:15:00+05:30"
- `events[]`: Wedding Muhurtham (26 Nov 2026, 9:15 AM to 10:00 AM)
- `eventDates`: Key-value map of ISO timestamps for generating multi-event calendar entries

### Venue & Maps
Edit `venue` in `editable/wedding-data.js`:
- `name`: "Brigade MLR Convention Centre"
- `address`: "7th Phase, J.P Nagar, Bengaluru - 560078"
- `mapsUrl`: "https://maps.app.goo.gl/3J1Rpe2PmLkNjE8T7?g_st=ic"

### Images & Media
Replace files directly in `editable/assets/` or update paths in `editable/wedding-data.js`:
- Monogram: `editable/assets/monogram.png`
- Couple walking illustration: `editable/assets/couple-walking.png`
- Hero floral arch backdrop: `editable/assets/hero-arch.jpg`
- Background music: `editable/assets/bgm.mp3`
- Opener video: `editable/assets/wedding-opener.mp4`
- Hero card (Page 1): `editable/assets/opener-card.jpg`

---

## Special Sections & Features

- **Cover Hero Page**: Displays the couple portrait card with symbol and names as the opening page of the invitation, opening directly with no flashing gates.
- **Royal Typography**: Highlighted Great Vibes calligraphy script in royal burgundy for couple names, Cinzel for invocations and relation titles, neat and uniform Cormorant Garamond serif for parents' names, and refined Cormorant Garamond for venue and event headings.
- **Background Music Player**: Floating audio control button playing "A Thousand Years" piano cover with auto-unlock on interaction.
- **Calendar Export**: Downloadable `.ics` file containing Wedding Muhurtham.
- **Scroll Reveal**: Sections fade and slide into view on scroll.
