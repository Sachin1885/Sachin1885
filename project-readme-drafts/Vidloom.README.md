# Vidloom

> Fork notice: this repository is forked from `shashank-633/Vidloom`. Review and document Sachin's specific contributions before presenting it as authored work.

## Overview

A peer-to-peer browser communication project for video and data exchange using WebRTC with a WebSocket signaling server.

## Features

- Direct browser-to-browser communication with WebRTC
- WebSocket signaling for SDP offers, answers, and ICE candidates
- STUN support for NAT traversal
- Optional TURN relay support
- React and TypeScript frontend

## Tech Stack

- Frontend: React, TypeScript
- Signaling server: Node.js, WebSocket
- Browser APIs: `RTCPeerConnection`, `getUserMedia`
- Connectivity: STUN/TURN

## Architecture

```text
Browser A <-> WebSocket signaling server <-> Browser B
     \___________ WebRTC media/data path ___________/
```

## Screenshots

Replace the current external image reference with a repository-local screenshot of the connection or call flow.

## Installation

Verify the repository's own folder names, then run the frontend and backend separately:

```bash
cd Frontend
npm install
npm run dev
```

```bash
cd Backend
tsc -b
node dist/index.js
```

## Environment Variables

No environment variables are documented in the current README. Document STUN/TURN configuration after verifying the implementation.

## Usage

Open `http://localhost:5173/` after the frontend and signaling server are running. Browser camera/microphone permission may be required.

## API

Document signaling message formats and connection events from the WebSocket implementation.

## Live Demo

[vidloom.netlify.app](https://vidloom.netlify.app/)

## Future Improvements

- Add a repository-local screenshot.
- Document STUN/TURN configuration and browser requirements.
- Add a verified signaling message reference.

## Author

[Sachin Kumar](https://github.com/Sachin1885)
