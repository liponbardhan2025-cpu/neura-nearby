# NEURA NEARBY

Live transit, flights, weather, nearby places, space and world data in one app.

Files: index.html, manifest.json, sw.js, icon.svg, icon-192.png, icon-512.png
Deploy: upload all files to the root of a GitHub repo, then Settings > Pages > Deploy from branch > main > / (root).


New: Ask AI tab (free built-in or your own Claude API key) and Deals tab (lowest-price search links for flights, trains, hotels).

v4: new themes (Plasma, Cyber, Solar, Ice), responsive phone/tablet/desktop layout, ISS orbital globe with next-pass estimate, animated orbit paths and flight trails.

v5: removed top status bar and tagline; World tab business data (billionaires, top companies, indices, commodities, crypto, news); health tips; stronger AI context.

v6: Nearby saves last results and falls back to a backup source; swipe left/right to change tabs (Alt+arrows on desktop); faster startup, lighter effects on phones, cached app shell.

v7: Nearby redesigned (category tiles, one selected by default, per-category loading, search, quick picks, backup source, error and empty states).

v8: Track tab merges several free ADS-B feeds (adsb.lol, airplanes.live, adsb.fi, adsb.one) with OpenSky fallback, auto-widen, clear empty/error states.

v9: new Stocks tab for the Indian market (Nifty 50, Sensex, Bank Nifty, Nifty IT, India VIX, USD/INR with live sparklines; NSE/BSE open-closed status in IST; searchable watchlist saved on device; large-cap gainers and losers; tap any stock for 1D to 5Y charts with 52-week range; India market news; SIP calculator; AI knows the live India data). Smoother UX across the app: scrollable 9-tab nav with readable labels, per-tab scroll memory, softer tab and dialog transitions, consistent press/hover feedback, toasts, back-to-top button, skeleton loaders, off-screen rendering savings, lighter effects on phones, iOS input-zoom fix, reduced-motion support.

v10: butter-smooth pass. Removed per-frame repaint effects (animated card borders, backdrop blur on cards, scanline overlay, animated aurora and grid), dark map tiles instead of a CSS filter while panning, directional tab slide, sliding nav pill, flicker-free live updates for Stocks, faster 0.65 s boot.

v11: Flight radar fix. airplanes.live now blocks non-feeder requests (HTTP 403), so it was removed. Radar uses adsb.lol + adsb.fi + adsb.one (no key needed) with a CORS-relay retry and OpenSky backup; flight tracking by callsign/hex tries every feed; clearer status and a Retry button.

v12: Map fix. CARTO basemap tiles now stamp "API KEY REQUIRED" on keyless requests, so they were removed. Maps use OpenStreetMap tiles (no key) with HOT and Esri as automatic backups, in the original dark style.
