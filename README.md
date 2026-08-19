# Kayla & Erik — Wedding Website

A static HTML/CSS wedding website. No build tools or server needed — just open
`index.html` in a browser, or upload the whole folder to any static host
(Netlify, GitHub Pages, etc.).

## Pages

- `index.html` — Home
- `agenda.html` — Wedding day schedule (placeholder times)
- `dress-code.html` — Colour palette + outfit inspiration
- `travel.html` — Venue (The Stone Cellar) + accommodation
- `rsvp.html` — RSVP
- `honeymoon-fund.html` — Honeymoon fund message

## Things to edit before sharing

1. **Photos** — the pasted images from our chat couldn't be saved to disk
   automatically, so save them yourself into `images/` using these filenames
   (or update the CSS/HTML references if you'd rather use your own names):
   - `images/hero.jpg` — home page hero background photo
   - `images/couple-1.jpg`, `images/couple-2.jpg`, `images/couple-3.jpg` —
     the "Our Photos" grid on the home page
   - `images/dresscode-1.jpg` through `dresscode-4.jpg` — only needed if you
     later replace the palette "Look" cards on the dress code page with real
     outfit photos
   - If a file is missing, the page falls back to a soft colour gradient, so
     nothing breaks — just looks plain until you add photos.

2. **RSVP link** (`rsvp.html`) — the RSVP button currently opens an email to
   `kayla.and.erik@example.com`. Replace that address with your real email,
   or swap the `href` for a Google Form / Typeform / other RSVP tool link.

3. **Honeymoon fund banking details** (`honeymoon-fund.html`) — replace the
   placeholder account holder, bank, account number, branch code, and SWIFT
   fields with your real banking details.

4. **Agenda** (`agenda.html`) — all times/events are placeholders, update
   them to match your actual day-of schedule.

5. **Welcome message** (`index.html`) — replace the placeholder paragraph
   with your own words.

6. **Dress code label** (`dress-code.html`) — replace the placeholder attire
   description (e.g. "Smart Casual") with your actual dress code. The four
   "Look" cards are palette-coloured placeholders — swap in real outfit
   photos whenever you have them.

The **accommodation table** (`travel.html`) is already filled in with the
real Stone Cellar guest list you sent over — just double check it's still
accurate closer to the day.

## Colour palette

| Name         | Hex       |
|--------------|-----------|
| Cream        | `#F0E6D2` |
| Baby Blue    | `#B9D6E3` |
| Sandy Brown  | `#C99162` |

Defined as CSS variables at the top of `css/style.css` — change them there to
retint the whole site.

## Fonts

Playfair Display (headings) + Cormorant Garamond (body), loaded from Google
Fonts. Requires an internet connection to render correctly; for a fully
offline site, self-host the font files instead.
