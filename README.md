# Tu Magia

A storefront and order-management site for a small independent shop,
built from scratch as a portfolio project.

## The problem

The shop sells through word of mouth and messaging apps. Customers have
no up-to-date catalogue to browse, and every order is arranged by hand.
This site gives customers a live catalogue they can order from, and gives the owner one place to manage requests.

## Two users

- **Customers** browse products and request what they want.
- **The owner** manages the catalogue and incoming requests from a dashboard.

## What it does (MVP)

- Browse products by category
- Request items and choose a collection time
- The owner is notified of each request and confirms it

Payment happens in person at collection, so the site handles requests,
not transactions.

## Out of scope (for now)

Online payment, delivery, subscriptions, customer accounts.

## Roadmap

Planned:

- Owner dashboard to view, confirm and manage requests
- Owner can add and edit products and photos
- Notifications when a new request arrives
- Calendar sync for confirmed collections
- A natural-language assistant (LLM API) so the owner can ask about
  their day, e.g. "what collections are scheduled today?", and get a
  plain-language answer drawn from their orders and calendar

## Tech

- Front end: HTML, CSS, vanilla JavaScript (PWA)
- Back end: Python (FastAPI)
- Database: PostgreSQL
- Hosting: Netlify (front end); back end host to be decided

## Why from scratch

Built without a store platform or front-end framework, to understand the full stack end to end: data model, API, security and deployment.

## Status

In active development. Setup instructions will be added once there is
something to run.
