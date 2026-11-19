# Anisha & Harjeet — Wedding invitation

Standalone static invitation for 17 January 2027. All artwork, music and fonts retain the original design, with Anisha first and the existing A&H seal.

## Preview and build

Run `npm start` in this folder, then open http://127.0.0.1:5173. No installation is needed. Use `PORT=5174 npm start` if another preview is running.

Run `npm run build` to produce this card's deployable `dist/` folder. `npm run preview` serves that build. Deploy this folder as its own repository with the included GitHub Pages workflow, or publish its `dist/` with a static host. Set `SITE_URL` to the final HTTPS URL when building to make the social image URL absolute.

## Details

- 17 January 2027: Anand Karaj at 10:00 AM; Lunch at 2:00 PM; Doli at 5:00 PM.
- Countdown and calendar downloads contain only this invitation's events. Times are IST (UTC+05:30).
- Directions use direct HTTPS Google Maps URLs with coordinates resolved from the supplied venue links. They open in the same tab without a short-link redirect or popup. Format: https://developers.google.com/maps/documentation/urls/get-started
- Portrait fade is confined to the bottom 7%, matching the reference card.
- Social previews reuse the existing date-free A&H seal because the original preview image contained both dates. No new image was created.

Edit wording in `index.html`, event data in `js/main.js`, styling in `css/style.css`, and matching calendar downloads in `assets/cal/`.
