# CaptionPop public site

Static pages for https://captionpop.app, hosted from this repository. All source is UTF-8; there is no build step or third-party frontend dependency.

## Current review

The brand palette follows the app: background #17221A, cards #212F25, raised surfaces #314636, accent #B6FF45, outlines #526556. Supplied logo SVGs and a 512px icon are under assets/.

Home distinguishes the available 1.4 Play tester release from the upcoming 1.4.1 features. Update those availability labels only after the corresponding Play release is accessible. Pricing text uses Google Play local pricing; do not hardcode one currency for every visitor.

For a local preview, run `python -m http.server 8080 --bind 127.0.0.1` from this directory. Open http://127.0.0.1:8080/.

Before publishing, review all five pages at narrow/mobile and desktop widths, check local links/assets, keyboard navigation and UTF-8. Keep privacy, terms, support and deletion URLs unchanged. Review content changes before merging to the publishing branch.
