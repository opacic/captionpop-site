# CapPops public site

Static pages for https://captionpop.app, hosted from this repository. All source is UTF-8; there is no build step or third-party frontend dependency.

## Current review

The site uses background #17221A, cards #212F25, raised surfaces #314636, dusty rose accent #D7A4B2 and outlines #526556. The current gradient mark and matching 512px app icon are under assets/.

Home describes the 1.4.1 test release and notes that access and features depend on the test release assigned in Google Play. Update public availability after the production release goes live. Pricing text uses Google Play local pricing.

For a local preview, run `python -m http.server 8080 --bind 127.0.0.1` from this directory. Open http://127.0.0.1:8080/.

Before publishing, review all five pages at narrow/mobile and desktop widths, check local links/assets, keyboard navigation and UTF-8. Keep privacy, terms, support and deletion URLs unchanged. Review content changes before merging to the publishing branch.
