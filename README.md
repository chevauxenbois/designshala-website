# Design Shala website

Event site for Design Shala, an IDHA Labs initiative. The first page is the event page for Career in Design (Winter Edition), Sat 28 Nov 2026.

- `public/` is everything that gets published. `public/index.html` is the whole site for now.
- Hosting: Cloudflare Workers static assets (free), set up in `wrangler.jsonc`, the same way as the Office Interio site. Every change to `main` deploys automatically to https://designshala.idhalabs.in (custom domain on the idhalabs.in Cloudflare zone; the workers.dev address https://designshala-website.harshkahateprojects.workers.dev also works).
- Register buttons have the class `form-link` and point to the Google Form https://forms.gle/hxsxakJ623B6pRJw5.
- Content in [BRACKETS] is placeholder: session time, recording/certificate answer. Footer contact: team.idhalabs@gmail.com, Instagram @idhalabs.

## Design

Printed conference programme look: powder-blue paper backdrop (texture embedded in the CSS), heading green #006015, body green #24503b, sage top bar #CEDBCF, lime #D4EF45 on buttons only. Hanken Grotesk for headings and body, Azeret Mono for small labels.

## Deploys

Cloudflare Workers Builds is connected to this repo (reconnected 2026-11-10). Each push to `main` builds and deploys automatically; check the Deployments tab in Cloudflare if a change does not appear.
