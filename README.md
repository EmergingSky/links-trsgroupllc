# links.trsgroupllc.com

Link-in-bio page for Chelsea S. Williams, RN. One static page (`index.html`), no build step.

## Before launch: swap in the real links

Every link that still needs a real URL has a `data-todo="..."` attribute and shows a red
**LINK NEEDED** tag on the page. Paste the real URL into `href`, then delete `data-todo="..."`
and the tag disappears.

| data-todo | What it should point to |
|---|---|
| `facebook`, `instagram`, `tiktok`, `linkedin` | Profile URLs |

TRS Residential links to https://residential.trsgroupllc.com/.

Photo: `assets/headshot.jpg` is cropped from the brand flyer. Replace it with a higher-resolution original when you have one.

Contact details (318-200-0780, admin@trsgroupllc.com, residential@trsgroupllc.com, 333 Texas Street, Suite 1300) come from the brand flyer and TRS referral guide.

## Compliance notes

- TRS Residential is described as housing only, with the no-medical-care disclaimer.
- Footer names Emerging Sky Holdings, LLC as the parent, per the playbook.
- Rae Sky Wellness: concierge RN services listed as of Nov 13, 2026, after Chelsea's LSBN email confirmation
  and her LDH review (solo RN only: no hired caregivers or 1099 contractors). Keep that email on file.
- No income or outcome promises anywhere on the page.

## Deploy (Netlify)

Netlify → Add new site → Import from Git → pick this repo. Build command: none. Publish directory: `.`
Then Domain management → Add a domain → `links.trsgroupllc.com`.

## Forms (Netlify Forms)

- `/checklist/` free checklist opt-in (form `checklist-optin`) -> `/checklist/thanks/` with the PDF in `/downloads/`
- `/coaching/welcome/` (noindex) is where the $1,000 coaching Stripe link redirects after payment
- `/wellness/` Rae Sky Wellness inquiry (form `wellness-inquiry`) -> `/wellness/thanks/`

After the first deploy: Site configuration > Forms > Enable form detection, then redeploy once.
Then Forms > Form notifications > Add notification > Email > admin@trsgroupllc.com for each form.
