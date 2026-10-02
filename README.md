# Nation Generator Wheels

Single-file HTML/JS browser game: spin-the-wheel nation generator plus a "play as your nation" strategy mode.

## Run
Open `index.html` in a browser. No build step, no dependencies.

## Setting
Alternate Victorian-era world where magic replaces gunpowder. Custom map using the Suzerain continents (Merkopa, Xina, Rika, Contana, Polaris + island chains). Fantasy religions and languages, with forge-your-own follow-up wheels.

## Features
- Generator wheels: size, population, ideology + sub-ideologies, doctrine, region, regional impact, landlocked, army, active-duty %, secret services, GDP, resources, HDI, background, great people; combo/heroic/disaster bonus wheels.
- Start by picking a region or spinning randomly.
- Play modes: yearly events, or Direct Command turn-based.
- Populated AI world with realistic cities, populations and armies; combined-arms war; treasury (taxes, debt, grand projects, institutions); vassals; era-based tech tree; leaderboard.
- Live as someone else (roles): Corporation, Pirate, Bandit, Citizen, Mercenary Company, Prophet, Revolutionary, Explorer — your nation becomes an AI state and you play a person/organization inside the living world.
- Living world: AI-to-AI diplomacy, alliances and wars; faith spread between states; migration; trade routes with piracy risk; terrain-driven hazard odds; Earth-mode real names, languages and cultures.
- Statecraft additions: colonies, peace terms (annex / ceded provinces / etc.), espionage (steal tech, plots, counter-intelligence), great people as named characters, industry panel with production/imports/exports.
- Map: 11 filters (political, terrain, relations, wealth, density, development, military, religion, language, alliances, provinces), provinces, tap a city to inspect it, expand view, 3D globe; history timeline and replay of border snapshots.
- Balance: diminishing-returns caps on stacked bonuses, overextension penalties, coalitions, AI economic/military parity; war odds match displayed modifiers.

## Dev notes
- Baseline SHA-256 of `index.html`: `ce466625a78b6decad7c278e18ae312d25189867fd7415eb7fa94e76d0c8640b`
- Never name a global helper `top` — it collides with `window.top` and silently breaks the wheel.
- Regression-test changes (multi-seed, multi-decade sims) before merging.
