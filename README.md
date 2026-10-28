# arahlabs.com — Cloudflare Pages

Static site, no build step.

## Deploy (direct upload)
1. Cloudflare dashboard → Workers & Pages → Create → Pages → Upload assets.
2. Project name: `arahlabs`. Drag in the contents of this folder (index.html at the root).
3. Deploy. You get `arahlabs.pages.dev`.
4. Custom domains → Set up a custom domain → `arahlabs.com` (and `www.arahlabs.com`). If the domain is already on Cloudflare DNS, records are added automatically.

## Deploy (Git)
Push this folder to a GitHub repo, connect it in Pages. Framework preset: None. Build command: empty. Output directory: `/`.

## Files
- index.html — the site (English + Bahasa Indonesia, switch in header, remembers choice)
- favicon.svg — tab icon
- og.jpg — image shown when the link is shared (WhatsApp, LinkedIn, etc.)
- _headers — security headers
- robots.txt, sitemap.xml — for search engines
