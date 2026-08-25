# Synapse

Text it. Email it. It handles it — and remembers everything.

Synapse is a personal assistant that lives in your inbox and your messages, not an app you have to open. It manages your tasks, your calendar, your groceries — even your stock watchlist — and every conversation is written to plain files you own, on a machine you control.

**[See it live →](https://kristianolsson.github.io/synapse/)**

## How it works

No new app to learn. Synapse listens on the channels you already have open, and answers back the same way.

- **Telegram** — Quick back-and-forth. Send a task, a link, a question — get a reply in seconds, with one-tap buttons for anything you can check off.
- **Email** — Ask it something that needs real research, or forward it a receipt. It stays quiet on routine confirmations and speaks up when there's something to tell you.
- **Scheduled** — Set it and forget it. A weekly market summary, a daily check-in, a Monday options scan — delivered on its own, without you asking.

## What it actually does

Not a chatbot that just talks — it takes real actions against your real accounts.

- **Tasks & reminders** — "Remind me every Saturday to call mom" becomes a real recurring reminder, delivered by text or email, no app required.
- **Calendar** — Reads and writes your Google Calendar in plain English — "move Thursday's dentist appointment to 3pm."
- **Groceries** — Builds and manages an Amazon Fresh cart from a running shopping list, remembering what you usually buy.
- **Stocks & investing** — Watches your portfolio, scans for options opportunities against your own thresholds, and sends a weekly market summary you can actually read.
- **Research & links** — Send it an article and it saves and summarizes it, filed under the right project automatically.
- **Email** — Drafts replies and organizes your inbox — drafts only. It never sends without you.

## Yours, not theirs

Every note is a file. Every file is yours, in a repository you control.

- **No vendor database** — Your tasks, links, and history live as plain Markdown in a git repository on your own machine, not locked inside someone else's app.
- **Full history, always** — Every change is a commit. Nothing is ever silently overwritten or lost.
- **Switch AI providers freely** — Not locked into one company's assistant. Works with Claude Code, Antigravity CLI, and Gemini CLI.

## Get started

Two open-source repos, plus your own private vault:

- **[synapse-engine](https://github.com/kristianolsson/synapse-engine)** — runs the assistant and talks to Email, Telegram, and your calendar.
- **[synapse-vault](https://github.com/kristianolsson/synapse-vault)** — a clean template vault with no personal data. Clone it, run one setup script, and it's yours.

This repo is the landing page — see [`index.html`](index.html).
