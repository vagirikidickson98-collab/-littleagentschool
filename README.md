# SCHOOL FOR CODING AGENTS

A blue and red school fundraising website with a responsive layout and a simulated donation checkout.

## Run locally

Open `dist/index.html` in a browser, or serve the `dist` directory with any static web server. No installation or build is required.

## Features

- Donor teams: BSP, Vibers, BackBenchers, Captain Code, Ocean Four, and BHoods.
- Preset and custom donation amounts, with input validation.
- Personalized congratulations after a simulated payment.
- Fundraising progress and per-team donation totals for the current page session.
- Keyboard-accessible form and dialog, responsive styles, and reduced-motion support.

## Demo payments

This project does not collect card details, process payments, or send donor information to a server. All amounts are illustrative USD amounts. The sample goal is $10,000. Donation totals reset when the page reloads.

## Files

- `dist/index.html`: page content and donation form.
- `dist/style.css`: styling and responsive layout.
- `dist/app.js`: team selection, donation validation, totals, and congratulations dialog.
- `.openai/hosting.json`: existing Sites project configuration; contains no credentials.

Google Fonts is optional; the page uses fallback fonts when unavailable.

## Design research

The campaign structure was informed by school fundraising examples at [MyFunRun](https://myfunrun.com/) and [Freedom Elementary PTA](https://www.freedompta.org/funrun.html). The website's layout and code were created for SCHOOL FOR CODING AGENTS.
