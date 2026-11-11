# Tu Magia

A storefront and order-management site for a small independent shop,
built from scratch as a portfolio project.

## The problem

The shop sells through messaging apps. Customers have no up-to-date catalogue to browse, and every order is arranged by hand.
This site gives customers a live catalogue they can order from, and gives
the owner one place to manage requests.

## Two users

- **Customers** browse products and request what they want.
- **The owner** manages the catalogue and incoming requests from a
  dashboard.

## What it does (MVP)

- Browse products by category
- Request items and choose a collection time
- The owner is notified of each request and confirms it

In the MVP, payment happens in person at collection, so the site handles requests, not transactions. Online payment through Mercado Pago comes after the MVP.

## Out of scope (for now)

Delivery, subscriptions, customer accounts. Online payment is planned (see Roadmap) but not part of the MVP.

## Roadmap

Planned:

- Owner dashboard to view, confirm and manage requests, built on the Django admin and simplified for a non-technical user
- Owner can add and edit products and photos
- Online payment with Mercado Pago, including payment confirmation by webhook
- Notifications when a new request arrives
- Calendar sync for confirmed collections
- A natural-language assistant (LLM API) so the owner can ask about their day, e.g. "what collections are scheduled today?", and get a plain-language answer drawn from their orders and calendar

## Tech

- Framework: Python (Django), with server-rendered templates
- Front end: HTML, CSS, vanilla JavaScript (PWA)
- Database: SQLite in development, PostgreSQL in production
- Hosting: Render
- Project structure
  app/ – the Django project (templates, static files, apps)
  docs/ – decisions log and project notes

## Why from scratch

Built without a store platform or front-end framework, to understand the full stack end to end: data model, back end, security and deployment.

## Status

In active development. Setup instructions will be added once there is something to run.
