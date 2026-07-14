# Bass Day Picker

A simple, free web tool that helps you pick the best days to fish for seabass around **Brighton and Shoreham** on the Sussex coast. It scores upcoming days using live weather and sea/marine conditions, so you can plan a session at a glance.

It's made of self-contained web pages — no install, no account, nothing to run on a server. Just open it in a browser.

## Live version

The tool is hosted on GitHub Pages:

**<https://mareksiem.github.io/Seabass-day-picker-brighton/>**

It's made up of three linked pages:

- **Bass Day Picker** ([`index.html`](index.html)) — the forecast and day scores.
- **Guide** ([`help.html`](help.html)) — how to read the scores and when to overrule them.
- **Log Catch Shortcut** ([`LogCatch-iphone-shortcut-guide.html`](LogCatch-iphone-shortcut-guide.html)) — an optional iPhone shortcut for logging catches at the waterside.

## Features

- Scores upcoming days for bass-fishing suitability based on weather and marine conditions
- Covers Brighton and Shoreham marks
- Links out to local tide times
- Runs entirely in your browser — nothing is stored or sent anywhere by the app itself

## How to use it

Just open the live link in any modern browser (phone, tablet, or computer) — no install, no account. It fetches current forecast data automatically and shows a ranked view of the days ahead, so an internet connection is required. On a phone you can tap the browser's share icon → **Add to Home Screen** for an app-style icon.

## Data sources and credits

This tool relies on free, third-party services. Thanks to them:

- **Weather & marine forecasts:** [Open-Meteo](https://open-meteo.com/) — data licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
- **Tide times:** links out to [Tide Times UK](https://www.tidetimes.org.uk/).
- **UI framework:** [React](https://react.dev/) (MIT licensed).
- **Fonts:** Google Fonts.

Live data belongs to its respective providers and is subject to their terms of use.

## ⚠️ Disclaimer — please read

This tool is provided **for general information and planning purposes only**. It is **not** a substitute for official tide tables, marine weather forecasts, coastguard advice, or your own judgement and experience.

Conditions at sea and on the shore can change quickly and can be dangerous. Always check official sources, tell someone your plans, wear appropriate safety gear, and never take risks based on this tool alone. **Fishing, and being near or in the water, is done entirely at your own risk.**

The author accepts no responsibility or liability for any loss, injury, or damage arising from use of this tool or reliance on the information it provides.

## Licence

The code in this project is released under the **MIT Licence** — see the [LICENSE](LICENSE) file. In short: you're free to use, copy, modify, and share it, but it comes with no warranty. The MIT Licence covers this project's own code only, not the third-party data or services listed above.

## Contributing / feedback

This is a personal hobby project shared freely. Suggestions and tweaks are welcome — feel free to open an issue or a pull request.
