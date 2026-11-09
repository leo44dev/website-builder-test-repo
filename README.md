# Leonard — personal website

A single-page personal site for Leonard: finance, business development, currency trading and business content.

## What's on the page
- **Live trading sessions** — shows which FX sessions (Sydney, Tokyo, London, New York) are open right now, in the visitor's local time.
- **Major pairs** — daily ECB reference rates via [Frankfurter](https://frankfurter.dev), with 30-day sparklines.
- **Position size calculator** — sizes a trade from balance, risk % and stop loss.
- **Liquid glass buttons** over an animated background, scroll-driven motion and animated chart canvases.

Everything is in `index.html` (HTML, CSS and JavaScript, no build step). The logo is `lion-logo.png`.

## Run it locally
Open `index.html` in a browser, or serve the folder (Windows PowerShell):

```powershell
powershell -ExecutionPolicy Bypass -File .claude/serve.ps1
```

Then visit http://localhost:8080.

## To do
- Replace the placeholder email and social links in the contact section of `index.html`.

Nothing on this site is investment advice.
