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
| `starter-kit` | Shared Living Starter Kit ($147) |
| `wellness-inquiry` | Rae Sky Wellness inquiry form |
| `facebook`, `instagram`, `tiktok`, `linkedin` | Profile URLs |

TRS Residential links to https://residential.trsgroupllc.com/.

Photo: `assets/headshot.jpg` is cropped from the brand flyer. Replace it with a higher-resolution original when you have one.

Contact details (318-200-0780, admin@trsgroupllc.com, residential@trsgroupllc.com, 333 Texas Street, Suite 1300) come from the brand flyer and TRS referral guide.

## Compliance notes

- TRS Residential is described as housing only, with the no-medical-care disclaimer.
- Footer names Emerging Sky Holdings, LLC as the parent, per the playbook.
- Rae Sky Wellness copy is education and inquiries only. **Needs confirmation** with the
  Louisiana State Board of Nursing before any hands-on care is marketed.
- No income or outcome promises anywhere on the page.

## Deploy (Netlify)

Netlify → Add new site → Import from Git → pick this repo. Build command: none. Publish directory: `.`
Then Domain management → Add a domain → `links.trsgroupllc.com`.
