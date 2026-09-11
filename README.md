# Interactive DM Screen

A blank, fully-customizable digital DM screen for 5th Edition (2024 rules). Single self-contained HTML file — no install, no build step, no server, no account. Open it in a browser and everything (edits, trackers, notes) autosaves to that browser.

**[Play it on itch.io →](https://melbius.itch.io/interactive-dm-screen)**

## What it is

The template ships completely blank on purpose — every location, trap, NPC, and stat block is a labeled placeholder showing the expected format. Click anything to edit it in place.

Included: campaign overview, sealed player goals, locations with sub-locations and map upload, traps with dice rollers, multi-stage encounter courses, a random events table, a configurable climax/finale tracker, a full combat tracker for any fight, a villain tracker (HP, Legendary Resistance, signature ability, plus a lightweight secondary-boss slot), custom stat blocks, an unlimited party roster, an NPC trust/relationship tracker, a session recap generator that auto-compiles from everything else, DM notes, and a Backup & Setup tab with JSON export/import and one-click reset to blank.

**Run more than one campaign from the same file.** A row of wax-seal icons in the header switches between fully separate campaign records — each with its own locations, party, villain, everything. Add, rename, duplicate, or delete a campaign without touching the others.

A **Play Mode** toggle locks all text fields and delete buttons during a session so nothing gets accidentally edited or removed mid-game, while dice, HP trackers, and round counters stay fully live. A **Print This Tab** button gives a clean, ink-friendly printout of whatever tab is open.

## Design

A steampunk alchemist's laboratory theme: copper and verdigris-teal palette, embedded Ultra (display) and Special Elite (gauge/dice readouts) faces, and a hand-drawn animated still — a bubbling flask, coiled condenser, turning gear, and pressure gauge — in the header. Riveted brass corner marks appear on every card, buttons emit a small steam-puff on click, HP bars carry a liquid shimmer, and a glowing acid-green accent is reserved for Ally/Active status so it still means something when it glows. All motion respects `prefers-reduced-motion`.

## Usage

Download `index.html` and open it in any modern browser. That's it — no build, no dependencies, no server.

## Repo contents

- `index.html` — the entire application (HTML/CSS/JS, no external dependencies)
- `itch_page_copy.md` — store page copy for the itch.io release

## Compatibility & legal

Built for 5th Edition (2024 rules) using only the SRD 5.2, released by Wizards of the Coast under the Creative Commons Attribution 4.0 International License. No proprietary settings, named monsters, or copyrighted adventure content are included. This is unofficial fan-made software and is not affiliated with, endorsed, or sponsored by Wizards of the Coast. Full attribution is included in the app itself (Backup & Setup tab).

## License / contributing

Free to use, modify, and share. Issues and pull requests welcome.
