# Aestheria: Moon & Tarot Ritual

Landing page and waitlist for Aestheria, a daily moon ritual app (in development): today's moon phase, a card of the
day and a minute for yourself, on the home screen. Served by GitHub Pages from `main`:
https://andronaft-2.github.io/aestheria/

## Positioning the page keeps
- One angle: a daily moon ritual. Not a cycle tracker, not a medical app, not an "AI astrologer".
- Reflection and mood only: no health or future predictions (see the disclaimer block).
- Privacy first: no account, everything stays on the phone, works offline.

## Files
- `index.html`: the page (English and Ukrainian, `?lang=uk` opens Ukrainian).
- `fonts/`: Cormorant Garamond and Manrope (SIL Open Font License), served from here so no visitor data goes to
  Google Fonts.
- `og.png`: the link preview (1200×630); `og-source.html` is its source, re-render it at 1200×630.

## Measuring the TikTok test
1. Create a free account at https://www.goatcounter.com (cookieless, no personal data) and pick a code, e.g. `aestheria`.
2. In `index.html` set `var GOATCOUNTER = "aestheria";`. The footer then says visits are counted.
3. Give every video its own link, e.g. `https://andronaft-2.github.io/aestheria/?utm_source=tiktok&utm_campaign=v01`.
   GoatCounter shows visits per campaign; compare them with new rows in the waitlist form.

Goal before building the MVP: a few hundred sign-ups in 2–3 weeks, 10–15 % of visitors from the videos joining.
