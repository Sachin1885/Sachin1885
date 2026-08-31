# Chat App

> Fork notice: this repository is forked from `shashank-633/Chat-app`. Review and document Sachin's specific contributions before presenting it as authored work.

## Overview

A real-time chat application where users create or join rooms and exchange messages over WebSocket. Empty rooms are deleted automatically.

## Features

- Create chat rooms
- Join existing rooms
- Real-time messaging with WebSocket
- Automatic deletion of empty rooms

## Tech Stack

- Frontend: React, TypeScript, Vite
- Backend: Node.js, TypeScript, WebSocket

## Architecture

```text
React/Vite client <-> WebSocket server
                         -> room lifecycle and message delivery
```

## Screenshots

The current repository contains screenshot references for the home page, room-name view, and chat room. Verify their repository-local paths before publishing this draft.

## Installation

Prerequisite: Node.js 16+ and npm or yarn.

```bash
git clone https://github.com/Sachin1885/Chat-app.git
cd Chat-app
cd Backend
npm install
npm run start
```

In another terminal:

```bash
cd Frontend
npm install
npm run dev
```

Open `http://localhost:5173/`.

## Environment Variables

No environment variables are documented in the current README. Add this section after verifying the source configuration.

## Usage

Start the backend first, then the frontend, create a room, and join it from another browser session.

## API

Document the WebSocket message and room events from the implementation. No REST route table is currently provided.

## Live Demo

[chat-app-theta-mocha-19.vercel.app](https://chat-app-theta-mocha-19.vercel.app/)

## Future Improvements

- Add a verified event-flow diagram.
- Document deployment configuration.
- Replace the inherited author section with accurate contribution details.

## Author

[Sachin Kumar](https://github.com/Sachin1885)
