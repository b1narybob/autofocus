# Autofocus

A working implementation of [Mark Forster's Autofocus](http://markforster.squarespace.com/autofocus-system/) time management system — a single self-contained HTML file, no build step, no backend.

Open `index.html` in any browser, or visit the live site via GitHub Pages.

## The method in brief

1. Write down everything you need to do, one line each. New items always go at the end — never sort, never prioritize.
2. Read through the current page quickly, without taking action.
3. Go through the page slowly, in order, until one item stands out.
4. Work on it as long as you feel like. If unfinished, re-enter it at the end of the list first, then cross it off where it was.
5. Keep going until a full pass finds nothing standing out, then move to the next page.
6. After the final page, loop back to the first live page.
7. If a first pass on a page finds nothing standing out, dismiss the whole page (highlighted, kept visible) — except the final page you're still writing on.

No due dates, no reminders, no priorities — the page explicitly forbids them. Time-specific commitments belong on a calendar.

## Features

- Ruled-notebook pages (configurable 10–40 items per page, default 25)
- Guided Focus pass: quick read → slow scan → timed work sessions
- Atomic re-entry (re-enter at end *before* crossing off, so your place is never lost)
- First-pass dismissal rule with final-page exemption
- Home and Workplace notebooks (add/rename as needed)
- Date marker on each day's first task
- Backlog dump, completion log, catch-up overview after 8+ hours away
- Dismissal reflection warning when re-adding a dismissed item
- JSON export/import backup

## Data

Everything is stored in your browser's `localStorage` on the device you use it on — nothing is sent anywhere. Use **Settings → Export JSON** to move your data to another device.

Full credit for the system to Mark Forster: http://markforster.squarespace.com/autofocus-system/
