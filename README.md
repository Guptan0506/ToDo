# To-Do

A simple, local to-do list that runs entirely in your browser — no install, no server, no account.

## Getting started

1. Download `todo.html`.
2. Double-click it (or open it with your browser).
3. Start adding tasks.

That's it. Move the file anywhere on your computer — Desktop, Documents, wherever you like.

## Features

- **Add tasks** — type into the input box and hit "Add," or press Enter.
- **Mark tasks done** — click the checkbox next to a task.
- **Delete tasks** — hover over a task and click the ✕ that appears.
- **Filter tasks** — switch between "All," "Active," and "Done" using the links above the list.
- **Add details (bullet points)** — click "+ Add details" under a task to open a text box. Each line you type becomes its own bullet point. Click "Edit details" later to update them.
- **Due dates** — click "+ Date" next to a task to pick a due date, or click an existing date to change it. Dates show as "Today," "Tomorrow," or the calendar date, and turn red if the task is overdue and not yet done.

## How your data is saved

Everything is stored locally in your browser using `localStorage` — nothing is sent anywhere, and there's no internet connection required after the page loads (aside from fetching the fonts the first time).

A few things to know:

- Your tasks are tied to the **browser** you use to open the file, not the file itself. Opening `todo.html` in a different browser (or a different browser profile) will show an empty list.
- Clearing your browser's site data/cache for this file can erase your tasks.
- There's currently no export/backup option — if you want to keep a permanent record, consider periodically noting down important tasks elsewhere.

## Customizing

The whole app lives in a single file (`todo.html`), so it's easy to tweak:

- **Colors** — edit the CSS variables at the top of the `<style>` section (`--bg`, `--green`, `--text`, etc.).
- **Font** — change the Google Fonts link and the `font-family` values.
- **Behavior** — the JavaScript at the bottom handles adding, editing, filtering, and saving tasks.

## Requirements

Just a modern web browser (Chrome, Firefox, Safari, Edge). No installation, no dependencies, no build step.
