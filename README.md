# webaworks-site

One-page corporate site for WEBA WORKS S.L., served at https://webaworks.com.

## Why this exists

Identifies the legal entity behind the `webaworks.com` domain for verification
flows (Google Play organization conversion, Apple, AWS, banking, etc.). Not a
marketing site for the products themselves.

## Stack

Plain HTML + CSS, no build step. Hosted on GitHub Pages from `main`. SSL
provisioned automatically by GitHub.

## Editing

Edit `index.html`, commit, push. Pages redeploys in ~30s.

## DNS

Apex `webaworks.com` resolves via four A records pointing at GitHub Pages
(185.199.108-111.153). DNS is managed at Squarespace (formerly Google Domains).
`www.webaworks.com` is a CNAME to `ew25.github.io`.

The `CNAME` file in the repo root is GitHub Pages' custom-domain marker — do
not remove it.
