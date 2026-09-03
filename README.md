# Downtown, On Foot

CWD Real Estate Investment's Tech Week Grand Rapids 2026 walking guide — the real downtown evening schedule (Sept 14–18), every marquee event's real address, and a heart-to-build-your-own-itinerary feature with a working print view.

Static site, single `index.html`, no build step, no backend. Hearting is local-only (browser `localStorage`) — no account, no server, no tracking.

Deployed via GitHub Pages at [ajpaschka.github.io/cwd-downtown-on-foot](https://ajpaschka.github.io/cwd-downtown-on-foot/).

Built as a reusable pattern, not a one-off — the mechanism (day-by-day event list, heart-to-itinerary, print view) is meant to be forked/adapted for the next downtown event week (this page itself hands off to ArtPrize on Sept 18) rather than rebuilt from scratch.

Originally prototyped as a Claude Artifact before migrating here for real `window.print()` support (the Artifact viewer's sandbox blocks script-triggered print/download dialogs) and a clean CWD-only URL with no Claude-viewer wrapper.

## TODO

- **Swap the footer mark for the full white CWD logo.** The footer currently uses a hand-cropped inline SVG of just the mark's two bracket paths (extracted from the wordmark viewBox), not the full logo. Per the CWD brand profile (`_shared/brand/profiles/cwd.md`), the canonical source is `CWD Projects/CWD CMYK Logo.svg` — dark backgrounds get the white version of that same master file, not a recreated or partial mark. Flagged 2026-09-03, not urgent.
