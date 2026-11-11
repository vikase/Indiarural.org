# indiarural.org

Website of the India Rural Development Fund (IRDF), a volunteer-run US 501(c)(3) that funds the Rural Development Foundation's schools in Telangana, India.

Static site. No build step. GitHub Pages serves `main` from the root.

- `index.html` — the whole site, one page.
- `data/ledger.json` — raised, sent and held by year, from IRS Form 990-EZ (ProPublica). Kept for reference; the page no longer shows it (board decision, Nov 2026).
- `data/schools.json` — the five institutions and their counts, from rdfindia.org. Update once a year.
- `img/` — the link-preview card (`share.jpg`, 1200 × 630). No hero photo for now: the Kalleda house photo was removed in Nov 2026 because the school moved to its own campus. Add campus photos here when RDF sends them.

## Before launch

- Remove the review strip at the top of `index.html` and resolve every `to confirm` mark.
- Add the PayPal button link to `#give-btn`.
- Domain: indiarural.org (CNAME file). DNS at Network Solutions: four A records for @ to GitHub Pages, CNAME www → vikase.github.io. MX (Google mail) untouched.

## Rules from the board (Sunil Erraballi, Nov 11, 2026)

- Use "donation" or "give". Do not use "gift".
- Do not centre the site on Kalleda. RDF runs five institutions. Mention Kalleda only as a fact of history.
- Do not show the Kalleda house photo. The school moved to its own campus.
- RDF is a separate legal entity. RDF is not a subsidiary of IRDF. Do not list the RDF address or the RDF email as an IRDF contact.
- The NJ General Assembly resolution is docs/NJassemblyResolution.pdf. It came from the old site through the Wayback Machine (capture of Feb 13, 2015).
- Wire instructions can go on the page. The page shows "Email us" until the treasurer sends the bank details.
