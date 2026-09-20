# Autofocus

A working implementation of [Mark Forster's Autofocus](http://markforster.squarespace.com/autofocus-system/) time management system — a single self-contained HTML file, no build step, no backend. Installable as a web app (PWA) with offline support.

Open `index.html` in any browser, or visit the live site via GitHub Pages.

## The method in brief

1. Write down everything you need to do, one line each. New items always go at the end — never sort, never prioritize.
2. Read through the current page quickly, without taking action.
3. Go through the page slowly, in order, until one item stands out.
4. Work on it as long as you feel like. If unfinished, re-enter it at the end of the list first, then cross it off here.
5. Keep going until a full pass finds nothing standing out, then move to the next page.
6. After the final page, loop back to the first live page.
7. If a first pass on a page finds nothing standing out, dismiss the whole page (highlighted, kept visible) — except the final page you're still writing on.

No due dates, no reminders, no priorities — the page explicitly forbids them. Time-specific commitments belong on a calendar.

## Features

- **Guided Focus pass** — the 8 steps as a walkthrough: quick read → slow scan → work sessions with a quiet count-up timer (no alarms, no limits)
- **Atomic re-entry** — re-enter at the end *before* crossing off, so your place is never lost; re-entry text is editable (re-phrasing is often best)
- **First-pass dismissal rule** with final-page exemption, exactly as the page describes
- Ruled-notebook pages (configurable 10–40 items per page, default 25), Home and Workplace notebooks
- Date marker on each day's first task
- History suggestions while typing (done + dismissed), with a reflection warning for dismissed items
- Backlog dump, completion log, catch-up overview after 8+ hours away
- Text-size setting, JSON export/import backup
- Works offline once loaded (service worker); add to Home Screen for an app icon

## Data

Everything is stored in your browser's `localStorage` on the device you use it on — nothing is sent anywhere. Use **Settings → Export JSON** to move your data to another device.

Full credit for the system to Mark Forster: http://markforster.squarespace.com/autofocus-system/
