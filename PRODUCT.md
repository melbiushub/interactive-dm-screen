# Product

<!-- impeccable:product-schema 1 -->

## Platform

web

## Users

Dungeon Masters running Dungeons & Dragons 5th Edition (2024 rules) tabletop campaigns, who want a single live-session reference screen — used at the table (laptop/tablet in front of the DM) to track combat, villains, party status, NPCs, and locations without juggling paper or multiple apps.

## Product Purpose

A free, self-contained digital DM screen that replaces paper reference binders. It houses every tracker a DM needs during a session (combat, villain/boss, party roster, NPC relationships, locations, traps, random events, climax pacing, session recap, notes) in one auto-saving file, and supports running multiple separate campaigns from the same file.

## Positioning

Unlike commercial VTT or campaign-manager SaaS products, this is a single downloadable HTML file: no install, no account, no server, no subscription. It works fully offline and keeps all data local to the user's browser. Free, with optional donations.

## Operating Context

Used live at the table during a session, sometimes printed via the built-in "Print This Tab" feature for a paper backup; also used between sessions for prep (session recap generator, notes, backup/restore). Distributed via GitHub Pages (source) and itch.io (storefront/listing).

## Capabilities and Constraints

- 14 tabs: Overview, Goals & Secrets, Locations, Traps & Encounters, Random Events, Climax Tracker, Combat Tracker, Villain, Stat Blocks, Party Tracker, NPC Relationships, Session Recap, Notes, Backup & Setup.
- localStorage persistence with multi-campaign switching, JSON export/import backup, and a Play Mode that locks text/delete controls mid-session.
- Must remain a single self-contained HTML file: no build step, no external runtime network dependency. Fonts must be embedded (base64) rather than loaded from a CDN, so the file keeps working fully offline with no internet connection.
- Must comply with the Wizards of the Coast Fan Content Policy and use only SRD 5.2 (CC-BY-4.0) content — no proprietary settings, monsters, or adventure content — and must carry SRD attribution in-app (Backup & Setup tab).
- Undecided: whether the next redesign may introduce a small amount of hand-authored inline SVG/CSS-only motion assets beyond what exists today (see current redesign request) — treated as in-scope since it doesn't break the offline/no-dependency constraint.

## Brand Commitments

Name: "Interactive DM Screen." Explicitly unofficial fan-made software, not affiliated with, endorsed, or sponsored by Wizards of the Coast — this disclaimer must remain visible in-app and in the README.

## Evidence on Hand

- `README.md`, `itch_page_copy.md` — existing product copy and store description.
- Live listing: itch.io (`melbius.itch.io/interactive-dm-screen`); source: GitHub (`melbiushub/interactive-dm-screen`).
- `demo_data_for_screenshots.json` — a fictional sample campaign ("The Sunken Spire") used only for illustration/screenshots, not real product content.

## Product Principles

1. Zero-friction, zero-cost access — no account, no install, no server, works fully offline.
2. Ship blank — every field starts as an editable placeholder; never fabricate a DM's campaign lore or content.
3. Never risk a DM's live session data — persistence and backup must be dependable above all else.
4. Stay legally clean — SRD-only content, clear fan-made attribution, no reproduction of copyrighted third-party art or stock photography.
5. Visual identity should feel like the DM's own worktable, not generic app chrome.
