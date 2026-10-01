# CH_RRAZ Project Reports

Chipotle Rita Ranch II project reports and coordination briefs.

Repository: [Harvey-Buck/CH_RRAZ-Project-Reports](https://github.com/Harvey-Buck/CH_RRAZ-Project-Reports)

## Reports

- [Construction Status](construction-status.html)
- [GC Coordination Brief](gc-coordination-brief.html)
- [Internal Project Status](internal-project-status.html)

## Repository Setup

- `main` is the working branch.
- `index.html` redirects to `construction-status.html`.
- Each report is a standalone HTML file; no build step is required.
- Construction status reports use the Friday week-ending date.
- The GC coordination brief and internal project status are maintained separately.

## Publishing

GitHub Pages is enabled with **Deploy from a branch**, using `main` and `/(root)` as the publishing source. HTTPS is enforced. Updates pushed to `main` are published by the GitHub Pages build and deployment workflow.

- [Live Construction Status](https://harvey-buck.github.io/CH_RRAZ-Project-Reports/)
- [Live GC Coordination Brief](https://harvey-buck.github.io/CH_RRAZ-Project-Reports/gc-coordination-brief.html)
- [Live Internal Project Status](https://harvey-buck.github.io/CH_RRAZ-Project-Reports/internal-project-status.html)

Deployment verified on October 1, 2026: the landing page redirects to the construction dashboard, which shows the Friday week-ending report dated 10/02/2026, 93% completion, and the gas-meter and water-meter date-unconfirmed watch items. All three report URLs returned HTTP 200.
