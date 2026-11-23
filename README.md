# The Nap Niwas — demo site

Demo website for **The Nap Niwas**, a private one-bedroom SOHO on the 10th floor of CCC Zirakpur (Block D&E, SOHO 1034), listed on [Airbnb](https://www.airbnb.co.uk/rooms/1820898712132260401).

Static site, no build step: everything lives in `site/` (`index.html` + `img/`).

## Run locally

```bash
py -m http.server 8765 --directory site
# open http://localhost:8765
```

## Deploy

Point any static host (Vercel, Netlify, GitHub Pages) at the `site/` folder.

## Demo notes

- Reviews are sample text; WhatsApp and Instagram links are placeholders.
- The "Ask Niwas" chat assistant is rule-based (no AI) and sends nothing: booking requests are shown as an email preview only.
- Drive times on the location radar are estimates.

Powered by Gen Clover.
