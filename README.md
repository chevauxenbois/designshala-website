# Design Shala website

Event site for Design Shala, an IDHA Labs initiative. The first page is the event page for Career in Design (Winter Edition), Sat 28 Nov 2026.

- `public/` is everything that gets published. `public/index.html` is the whole site for now.
- Hosting: Cloudflare Workers static assets (free), set up in `wrangler.jsonc`, the same way as the Office Interio site. Every change to `main` deploys automatically to https://designshala.harshkahateprojects.workers.dev once the repo is connected in Cloudflare.
- Register buttons have the class `form-link` and point to `https://forms.gle/REPLACE-WITH-YOUR-FORM`. Replace every occurrence with the real Google Form link.
- Content in [BRACKETS] is placeholder: session time, email, WhatsApp, Instagram handle, recording/certificate answer.

## Design

Printed conference programme look: powder-blue paper backdrop (texture embedded in the CSS), heading green #006015, body green #24503b, sage top bar #CEDBCF, lime #D4EF45 on buttons only. Hanken Grotesk for headings and body, Azeret Mono for small labels.
