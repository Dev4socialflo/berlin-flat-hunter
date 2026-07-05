# 🧡 Capy's Berlin Flat Hunt

A gift: a personal flat-hunting sidekick for Berlin, fronted by **Capy the capybara** — bag packed, bike ready.

Paste an ImmoScout listing (link or text) and Capy reads it, checks the commute to work and which supermarkets (Edeka, Rewe, Lidl…) are nearby, then scores the flat 0–100 against what actually matters — and tells you straight: *Capy approves* or *Capy says nope*.

## Features

- **One-paste add** — paste the listing link or its text; the parser extracts Warmmiete, Kaltmiete, Zimmer, m², floor, Aufzug (including "kein Aufzug"), Balkon, Baujahr → Neubau, provisionsfrei, and the address
- **Dealbreakers** auto-reject: no elevator above 1st floor, top floor, outside the S-Bahn Ring, fewer than 3 Zimmer
- **Weighted scoring** with a per-criterion "Why?" breakdown — commute, no-stairs, Ring, Neubau, supermarket, space, rent value, balcony, no fee
- **Auto location lookup** — commute time to work (OpenStreetMap/OSRM, or OpenRouteService with a free key) and named supermarket chains with distances (Overpass)
- **Capy himself** — mood faces per score, a verdict on every flat, 🏆 Capy's pick on the best one, and he cycles across the screen while lookups run
- **Private** — everything lives in the browser's localStorage; export/import as JSON

## Run it

It's a single self-contained file — no build, no dependencies:

```
open index.html
```

or serve it: `python3 -m http.server 4599`

## Make it yours

Open **⚙ Settings** for dealbreakers, importance sliders, budget thresholds, work address, and **💌 Personal touch** (the names in Capy's greeting).

Made with ♥ and a capybara in Berlin.
