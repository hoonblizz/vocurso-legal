# vocurso-legal

Public hosting for Vocurso (Sloth Lab) Privacy Policy and Terms of Service.

Hosted via GitHub Pages at:
- Index: https://hoonblizz.github.io/vocurso-legal/
- Privacy: https://hoonblizz.github.io/vocurso-legal/privacy.html
- Terms: https://hoonblizz.github.io/vocurso-legal/terms.html

## How it works

Pure static HTML + a tiny client-side markdown renderer (`marked` via CDN).
The markdown source lives inline in `privacy.html` and `terms.html` as a
`<script type="text/markdown">` block. To update content:

1. Edit the markdown block in `privacy.html` or `terms.html`
2. Bump the **Last updated** date in the page footer + `index.html` footer
3. Commit + push — GitHub Pages redeploys in ~60s

## Source of truth

The canonical markdown drafts live in the main app repo at:
- `sloth-lab-career/docs/privacy-policy-v2.md`
- `sloth-lab-career/docs/terms-of-service-v2.md`

Changes should land there first (with review history), then be copied here.
The internal-draft warning blocks in those files are intentionally **omitted**
from the public-facing pages.

## License

The legal text is meant for public consumption; the HTML/CSS scaffolding is
MIT-licensed.
