# links.trsgroupllc.com

Link-in-bio page for Chelsea S. Williams, RN. One static page (`index.html`), no build step.

## Before launch: swap in the real links

Every link that still needs a real URL has a `data-todo="..."` attribute and shows a red
**LINK NEEDED** tag on the page. Paste the real URL into `href`, then delete `data-todo="..."`
and the tag disappears.

| data-todo | What it should point to |
|---|---|
| `discovery-call` | $20 Business Discovery Call booking page |
| `nursepreneur-session` | $147 NursePreneur Strategy Session booking |
| `real-estate-session` | $247 Real Estate Acquisition Strategy Session booking |
| `shared-living-coaching` | Shared living setup coaching inquiry form |
| `trs-site` | TRS Residential website (currently set to https://trsgroupllc.com/, confirm) |
| `trs-referral` | Resident referral / availability form |
| `wellness-interest` | Rae Sky Wellness interest list or contact form |
| `facebook`, `instagram`, `tiktok` | Profile URLs |
| `email` | `mailto:you@trsgroupllc.com` |

Photo: replace `assets/headshot.svg` with a square headshot (600x600 JPG works well) and update the `src` in `index.html`.

## Compliance notes

- TRS Residential is described as housing only, with the no-medical-care disclaimer.
- Rae Sky Wellness copy is consulting and education only. **Needs confirmation** with the
  Louisiana State Board of Nursing before any hands-on care is marketed.
- No income or outcome promises anywhere on the page.

## Deploy (Netlify)

Netlify → Add new site → Import from Git → pick this repo. Build command: none. Publish directory: `.`
Then Domain management → Add a domain → `links.trsgroupllc.com`.
