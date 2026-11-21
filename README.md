# Lamma site (GitHub Pages)

- `privacy.html` — privacy policy URL for App Store Connect.
- `index.html` — support / marketing URL.
- `seasonal.json` — seasonal word packs the app downloads (no app update needed).
  Bump `version` on every change. Packs need `id`, `title`, optional `icon` (SF Symbol),
  `from`/`until` (yyyy-MM-dd, Riyadh time) and at least 12 `words` (`w`, optional `h` hint).
  Keep `Lamma/Resources/seasonal.json` in the app as the offline copy.
- `app-ads.txt` — add once the AdMob account exists (`google.com, pub-XXXX, DIRECT, f08c47fec0942fa0`).
