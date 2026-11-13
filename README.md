# links.trsgroupllc.com

Link-in-bio page for Chelsea S. Williams, RN. One static page (`index.html`), no build step.

## Before launch: swap in the real links

Every link that still needs a real URL has a `data-todo="..."` attribute and shows a red
**LINK NEEDED** tag on the page. Paste the real URL into `href`, then delete `data-todo="..."`
and the tag disappears.

| data-todo | What it should point to |
|---|---|
| `discovery-call` | $20 Business Discovery Call booking page |
| `free-checklist` | Shared Living Home Launch Checklist opt-in |
| `birthday-bundle` | $39 mini bundle payment link (remove the whole button after Sun, Nov 15, 2026) |
| `nursepreneur-session` | $147 NursePreneur Strategy Session |
| `real-estate-session` | $247 Real Estate Acquisition Strategy Session |
| `starter-kit` | Shared Living Starter Kit ($147 founding price) |
| `wellness-inquiry` | Rae Sky Wellness inquiry form |
| `facebook`, `instagram`, `tiktok`, `linkedin` | Profile URLs |
| `email`, `email-text` | `mailto:` your email (also replace the shown address) |
| `phone` | `tel:+1318...` (also replace the shown number) |

TRS Residential links to https://residential.trsgroupllc.com/.

Photo: replace `assets/headshot.svg` with a square headshot (600x600 JPG works well) and update the `src` in `index.html`.

## Compliance notes

- TRS Residential is described as housing only, with the no-medical-care disclaimer.
- Footer names Emerging Sky Holdings, LLC as the parent, per the playbook.
- Rae Sky Wellness copy is education and inquiries only. **Needs confirmation** with the
  Louisiana State Board of Nursing before any hands-on care is marketed.
- No income or outcome promises anywhere on the page.

## Deploy (Netlify)

Netlify → Add new site → Import from Git → pick this repo. Build command: none. Publish directory: `.`
Then Domain management → Add a domain → `links.trsgroupllc.com`.
