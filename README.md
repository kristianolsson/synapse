# Synapse

Text it. Email it. It handles it — and remembers everything.

Synapse is a personal assistant that lives in your inbox and your messages, not an app you have to open. It tracks the projects you're actually working on, runs the research you'd otherwise forget to do, and takes a quick note the moment you think of it — every conversation written to plain files you own, on a machine you control.

**[Learn more →](https://kristianolsson.github.io/synapse/)**

![Synapse mascot](vault-profile.jpg)

## How it works

No new app to learn — and most of what it does happens before you'd think to ask, running quietly in the background. When you do reach for it, it's already on the channels you have open.

- **Scheduled** — The workhorse channel. A reminder can be a one-line nudge, or a fully custom recurring task with its own prompt and schedule — a market summary, a daily check-in, a deep weekly analysis. Build it once, and it runs on its own from then on.
- **Email** — Ask it something that needs real research, or forward it a receipt. It stays quiet on routine confirmations and speaks up when there's something to tell you.
- **Telegram** — Quick back-and-forth. Send a task, a link, a question — get a reply in seconds, with one-tap buttons for anything you can check off.

## What ships with it

Not a chatbot that just talks — it takes real actions against real accounts. Each of these is a starting point, not a limit (see below).

- **Projects** — Every ongoing thing gets its own file — a home project, a side build, a trip — organized by area, with a live dashboard of what's active. Finish one and it's archived automatically.
- **Research & links** — Send it an article and it saves and summarizes it, filed under the right project automatically.
- **Tasks & reminders** — "Remind me every Saturday to call mom" becomes a real recurring reminder, delivered by text or email, no app required.
- **Email** — Drafts replies and organizes your inbox — drafts only. It never sends without you.
- **Stocks & investing** — Watches a portfolio, scans for options opportunities against thresholds you set, and sends a weekly market summary worth actually reading.
- **Calendar** — Reads and writes your Google Calendar in plain English — "move Thursday's dentist appointment to 3pm."
- **Groceries** — Builds and manages an Amazon Fresh cart from a running shopping list, remembering what you usually buy.

## Built to be changed

Every module above comes from a small protocol file — plain instructions the assistant reads before it acts. Once you clone the vault template, those files are yours: tighten a rule, add a module for something you track that isn't listed here, or delete one you'll never touch. A few ideas:

- **Recurring research, not just reminders** — A scheduled task that actually goes and looks — this week's schedule, last week's market move, the storylines heading into a big game — written up and delivered before you'd have thought to check.
- **A project that grows by text** — Think out loud over a few messages, or fire off a one-line update mid-day — it lands in the right project file, no app to open, no thread to lose.
- **A daily check-in** — Two reminders and a short protocol turn it into a habit tracker — sleep, workouts, a no-spend month, whatever you're actually trying to build.

## Yours, not theirs

Every note is a file. Every file is yours, in a repository you control.

- **No vendor database** — Your tasks, links, and history live as plain Markdown in a git repository on your own machine, not locked inside someone else's app.
- **Full history, always** — Every change is a commit. Nothing is ever silently overwritten or lost.
- **Switch AI providers freely** — Not locked into one company's assistant. Works with Claude Code and Antigravity CLI.

## Get started

Two repos, plus your own private vault:

- **[synapse-engine](https://github.com/kristianolsson/synapse-engine)** — runs the assistant and talks to Email, Telegram, and your calendar.
- **[synapse-vault](https://github.com/kristianolsson/synapse-vault)** — a clean template vault with no personal data. Clone it, run one setup script, and it's yours.

This repo is the landing page — see [`index.html`](index.html).
