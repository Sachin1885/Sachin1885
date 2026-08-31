# Sachin Kumar - Developer OS Portfolio

## Overview

A responsive developer portfolio with a project explorer, GitHub activity, guided tour, contact workflow, and protected admin view.

## Features

- Responsive single-page portfolio
- Boot experience and guided tour
- Project explorer and GitHub activity
- Contact form with SQLite persistence and Gmail notifications
- Token-protected admin panel

## Tech Stack

- Frontend: React, TypeScript, Tailwind
- Backend: Node.js, Express
- Data: SQLite
- Deployment: Render

## Architecture

```text
React client -> Express server -> SQLite contact storage
                         -> Gmail notifications
                         -> token-protected admin API
```

## Screenshots

Add repository-local screenshots of the portfolio landing view, project explorer, contact form, and admin view.

## Installation

```bash
npm install
cp .env.example .env
npm start
```

For frontend development:

```bash
npm run client:dev
```

## Environment Variables

Configure the variables listed in `.env.example`. Keep email credentials and the admin token private.

## Usage

Open `http://localhost:3000` after starting the server.

## API

Document the contact and admin routes from `server.js` before publishing a route table.

## Live Demo

[portfolio-10sv.onrender.com](https://portfolio-10sv.onrender.com/)

## Future Improvements

- Add screenshots and a public architecture diagram.
- Add route-level API documentation.
- Add deployment troubleshooting notes.

## Author

[Sachin Kumar](https://github.com/Sachin1885)
