# Creative Half-Life

Ads lose their pull over time. Enter how many days an ad has run, its click-through rate when it started and its click-through rate today. The page shows how far it has fallen and roughly how long until it halves at that pace.

Open `index.html` in any browser. No build step, no dependencies, no network calls.

- **Verdict:** whether the ad needs replacing, based on the pace of the fall.
- **Shows:** the drop so far and the time to lose half.
- **Arithmetic:** half-life = days x ln 2 / ln(start / now). The full formula is on the page.
- **Share:** a paper-ground PNG card, and the URL hash carries your numbers.

It uses two readings, so it is a rough guide. Example figures are made up.

## License

Code is MIT licensed ([LICENSE](LICENSE)). The bundled fonts (Bricolage Grotesque, Archivo) are SIL OFL 1.1, with licenses in `fonts/`. The ben.j.ads wordmark and footnote mark in `logo/` are Ben Johnston's brand assets and are not covered by the MIT license.
