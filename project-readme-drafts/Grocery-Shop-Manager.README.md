# Grocery Shop Manager

## Overview

A full-stack shop management application for inventory, pricing, billing, sales history, and credit account workflows.

## Features

- JWT authentication, profile, and password reset flows
- Admin user management
- Inventory and pricing management
- Billing with sale line items
- Daily sales summaries and bill history
- Credit account (khata/udhaar) tracking
- Progressive Web App support

## Tech Stack

- Frontend: HTML, CSS, Vanilla JavaScript
- Backend: Node.js, Express
- Database: PostgreSQL via `pg`
- Authentication: `jsonwebtoken`, `bcrypt`

## Architecture

```text
Browser pages -> Express server -> PostgreSQL
                       -> JWT authentication
                       -> inventory, billing, sales, and credit workflows
```

## Screenshots

The repository documents these local screenshots:

- `assets/screenshots/login.png`
- `assets/screenshots/dashboard.png`
- `assets/screenshots/billing.png`
- `assets/screenshots/admin.png`

## Installation

Prerequisites: Node.js 18+, npm, and PostgreSQL.

```bash
git clone https://github.com/Sachin1885/-Grocery-Shop-Manager.git
cd -Grocery-Shop-Manager
npm install
npm start
```

Open `http://localhost:4000`.

## Environment Variables

Create `backend/.env` with values for `PORT`, `HOST`, `JWT_SECRET`, and `DATABASE_URL`. Never commit secrets.

## Usage

Use the login, dashboard, billing, and admin pages after the server and database are running.

## API

Add a route table covering authentication, inventory, billing, sales, and credit-account endpoints after verifying routes in `backend/`.

## Live Demo

The repository currently lists a Render homepage, but it should be repaired and verified before publishing it as a live demo.

## Deployment

The repository includes `render.yaml` for a Render web service and managed PostgreSQL setup.

## Future Improvements

- Add a verified deployment health check.
- Add a data model and request-flow diagram.
- Add API examples and troubleshooting notes.

## Author

[Sachin Kumar](https://github.com/Sachin1885)
