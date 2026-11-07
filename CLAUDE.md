# Foresight support site: agent instructions

Static website for Foresight Financial Planner: `index.html`, `privacy.html`, `terms.html`, plus images. Served at foresightfinancialplanner.com (`CNAME`). Plain HTML and CSS, no build step. The app opens these pages with a `?lang=` parameter so they match the app's language, so keep that working.

## Rules

- GitHub is the master copy. Push before calling work done.
- Changes to `privacy.html` and `terms.html` are legal text (custom terms under Saudi law, SCCA arbitration in Riyadh, Apple third-party beneficiary clause). Don't edit wording unless Yasser asks, and show him the exact change first.
- Never deploy, change DNS or the `CNAME`, send messages, or make purchases without asking Yasser in the thread.
- The site has a hidden, password-protected analytics page. Never add credentials or secrets to this repo.
- No weather language, no ads or trackers. Use relative links so pages work at any base URL.
- English and Arabic must stay in step. Arabic copy reads native-first, and "Foresight" stays in Latin script.
- Check changes by opening the HTML in a browser at phone width before saying done.

Yasser is non-technical. Plain language, short replies.
