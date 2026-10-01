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
- Balance: diminishing-returns caps on stacked bonuses, overextension penalties, coalitions, AI economic/military parity; war odds match displayed modifiers.

## Dev notes
- Baseline SHA-256 of `index.html`: `e47f22cf332fc44fcd08bf3a402fc523e968aeae468f0477d5c5945f81aac1cd`
- Never name a global helper `top` — it collides with `window.top` and silently breaks the wheel.
- Regression-test changes (multi-seed, multi-decade sims) before merging.
