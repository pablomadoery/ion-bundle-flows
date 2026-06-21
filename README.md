# ION DTN — Interactive Bundle Flow (BP / LTP)

A single-page interactive diagram visualizing bundle flows through the
[ION](https://sourceforge.net/projects/ion-dtn/) Delay/Disruption Tolerant
Networking stack — Bundle Protocol (BP) over Licklider Transmission Protocol (LTP).

## Contents

- `ion-bundle-flows.html` — the self-contained interactive diagram (no build step, no dependencies).

## Running locally

Open `ion-bundle-flows.html` directly in a browser, or serve the folder:

```bash
npx serve .
```

## Deployment

This site is deployed as a static project on [Vercel](https://vercel.com).
`vercel.json` rewrites the site root (`/`) to `ion-bundle-flows.html`.
