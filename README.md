# Bert’s A/C and Heating — website (first draft)

One-page static site for **Bert’s A/C and Heating**, Cypress, Texas.

This is a first draft to show Bert. Not a legal-name page. Not a bio. Not the final brand system.

Visible brand: **Bert’s A/C and Heating**  
Optional line on the site: “Keeping Cypress cool.”  
Possible later domain: `keepcypresscool.com`

English is the home page. Spanish is a full connected mirror at `es/index.html` (`/es/`). Same phone, same services. Header and footer switch: **English / Español**.

## Open locally

No build step. No npm.

- Double-click `index.html`, or
- From this folder: `python3 -m http.server 8080` then open that in a browser

## Phone number

Every primary button is tap-to-call:

- Human-readable: `(832) 473-8785`
- `tel:` link: `tel:+18324738785`
- Text-us (same number): `sms:+18324738785`

If the number changes, search the folder for `832` and `+18324738785` and replace both.

## Connect this folder to Netlify

1. Push **this folder** to GitHub as the repo root (repo name `berts-ac-and-heating` or `keep-cypress-cool`).
2. In [Netlify](https://app.netlify.com/): **Add new site → Import an existing project → GitHub**.
3. Pick the repo.
4. **Build command:** leave empty.
5. **Publish directory:** `.` (site root).
6. Deploy.
7. Later: Domain management → add `keepcypresscool.com`.

`netlify.toml` in this folder already points publish at `.`.

## Placeholders still to fill

- License number (page currently says “Licensed & insured — details on request”)
- Hours (page currently says “Hours: call to check”)
- A real truck / shop photo **only if Bert wants one** — do not add smiling stock people
- Confirm same-day language if availability changes
- Confirm UV / heat-pump wording if Bert wants it stronger or gone

## What this is not

No blog, shop, login, fake reviews, fake awards, or “#1 in Cypress.”
