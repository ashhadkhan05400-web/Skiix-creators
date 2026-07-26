# Skiix — Supportive Creators

Signup page for Skiix's Supporting Creators program. Collects a creator's name and email pre-launch so they can get first pick of collabs before everyone else finds out.

**Live:** [skiix-creators.vercel.app](https://skiix-creators.vercel.app)

## What's in here

A single static page (`Creator forms/index.html`) — no build step, no framework.

- Name + email form
- Submissions go to Formspree — every signup lands in the Formspree dashboard, no backend needed
- Skiix brand: black background, blue-to-white gradient accents, Plus Jakarta Sans

## Setup

1. Clone the repo
2. Make sure `skiix-logo.jpeg` sits in the same folder as `index.html`
3. Open `index.html` and confirm the Formspree endpoint in the `<script>` tag matches your form:
4. Deploy — this repo is connected to Vercel and deploys automatically on push to `main`

## Viewing signups

Every submission shows up in your [Formspree dashboard](https://formspree.io) — exportable as CSV, and Formspree can email you on each new signup too.

## Stack

Plain HTML/CSS/JS. No dependencies, no package.json.
