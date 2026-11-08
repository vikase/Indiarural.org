# indiarural.org

Website of the India Rural Development Fund (IRDF), a volunteer-run US 501(c)(3) that funds the Rural Development Foundation's schools in Telangana, India.

Static site. No build step. GitHub Pages serves `main` from the root.

- `index.html` — the whole site, one page.
- `data/ledger.json` — raised and sent, by year, from IRS Form 990-EZ (ProPublica). Update once a year.
- `data/schools.json` — the five institutions and their counts, from rdfindia.org. Update once a year.
- `img/` — Kalleda house photo and the link-preview card (`share.jpg`, 1200 × 630).

## Before launch

- Remove the review strip at the top of `index.html` and resolve every `to confirm` mark.
- Add the PayPal button link to `#give-btn`.
- Add the file `CNAME` with the line `indiarural.org`, then change the DNS records: A records for the apex to GitHub Pages, CNAME `www` → `vikase.github.io`. Do not touch the MX records.
