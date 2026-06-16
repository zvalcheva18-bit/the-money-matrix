# The Wolf Files — Landing Page

Self-contained landing page for **The Money Matrix** ($19.99 PDF). Built from the page spec.
Mobile-first, dark "dossier" aesthetic, single conversion goal.

## Files
- `index.html` — the whole page (HTML + CSS + JS inline; only external dep = Google Fonts)
- `img/wolf-money-cut.png` — hero (money pose)
- `img/wolf-smirk-cut.png` — Wolf card (smirk pose)
- `img/wolf-talking-cut.png` — offer header (talking pose)
- (`*-cut.png` = backgrounds removed; the originals `wolf-money/smirk/talking.png` are kept too)

## Preview
Just double-click `index.html`, or:
```
open index.html
```

## Before launch (3 things)
1. **Checkout URL** — open `index.html`, find `var CHECKOUT_URL =` near the bottom, paste your real Whop link. That one line sets all 4 buttons + the sticky bar.
2. **Policy pages** — in the footer, set the `href` on Terms / Privacy / Refunds.
3. **Page numbers** — confirm the 8 `p.NN` chips in the Contents match the final PDF.

## Deploy (any of these, all free)
- **Netlify Drop** — drag this `landing/` folder onto app.netlify.com/drop → instant URL.
- **Cloudflare Pages / Vercel** — point at the folder.
- **GitHub Pages** — push the folder, enable Pages.
Then put that URL in your IG bio / link-in-bio for the "Comment WOLF" funnel.

## Notes
- Sticky "$19.99" button appears on mobile after the hero scrolls away; hidden on desktop.
- Each of the 3 wolf poses is used exactly once (money / smirk / talking), per spec.
- No build step, no framework — edit text directly in `index.html`.
