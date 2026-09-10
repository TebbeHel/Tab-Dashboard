# Tab Dashboard

A personal start page for Google Chrome. It replaces the empty new tab with a clean dashboard: clock, search, weather, rain radar, headlines and my most used links, grouped into Daily, AI, Finance, Music and Streaming.

**Open it:** https://tebbehel.github.io/Tab-Dashboard/

## What it does

* Clock and date
* Search bar that goes to Gemini (Enter) or Google (button)
* Current weather and a 7 day forecast for your location, via Open-Meteo
* Live rain radar, via Windy
* Latest headlines from tagesschau.de
* Link tiles that open in a new tab

Everything lives in a single `index.html`. No build step, no backend, no API keys.

## Customise

Links, groups, city fallback, news source and clock settings are in the `CONFIG` block at the top of `index.html`.
