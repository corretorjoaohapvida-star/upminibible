# Mini Bible US upsell

Static English upsell page. USD18 exclusive Black Friday offer; regular USD40.

## Vercel
Import this repository. Framework preset: Other. Root directory: repository root. No install or build command is required. Output directory: `.`.

`index.html` is the main entrypoint; `upsell.html` is an equivalent entrypoint. Assets and scripts use relative paths.

## Hotmart
The official salesFunnel widget controls the purchase decisions. Configure this deployed page as the upsell step in the active Hotmart funnel. Opening the page directly without a preceding purchase can show a Hotmart message requiring an active purchase. A real post-purchase test is still required.

The 10-minute countdown is stored per browser session, survives reload and stops at zero. It does not enforce a price expiration or change the Hotmart funnel. Configure the funnel to honor the promise that this promotion is not offered again after continuing.

`thank-you.html` is a local fallback. Access and support links in offer-config.js are pending; do not use it as the final delivery destination until those are configured. The 38-theme production deliverable is separate from these page assets.
