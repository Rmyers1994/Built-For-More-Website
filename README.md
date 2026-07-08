# Built For More — Landing Page

Single static HTML file. No build step. Google Fonts is the only external request.

## BFM_CONFIG (top of index.html)

Already wired:
- All three tool URLs (pension, DROP, 457vsot subdomains)
- KIT_LANDING_URL — until a form ID is added, the signup buttons open
  builtformoreusa.kit.com/0a7a668d3c in a new tab. Nothing is ever a dead link.

One optional upgrade — KIT_FORM_ID:
With the numeric form ID filled in, signups happen inline on the page
(no redirect, higher conversion). To find it in Kit:
Grow -> Landing Pages & Forms -> click your form -> look at the browser
address bar: app.kit.com/forms/1234567/edit -> the number is the ID.
Paste it as KIT_FORM_ID: "1234567" and redeploy.

The form's incentive email in Kit should deliver the Retirement Checklist
PDF — that is what enforces email-before-download.

## Deploy

Replace the files in the existing landing-page GitHub repo with these
(index.html + README.md) and commit — Vercel redeploys automatically.

Education only — not financial advice.

(c) Built For More - builtformoreusa.com
