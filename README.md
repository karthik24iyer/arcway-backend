# Arcway Backend

Node.js WebSocket server that manages terminal sessions and PTY interfaces on the host machine.

## Requirements

- Node.js 18+
- npm

## Setup

```bash
npm install
```

## Run

```bash
# Production
npm start

# Development (hot reload)
npm run dev
```

Server starts on `0.0.0.0:8080` by default.

## Configuration

Edit `config/default.json` to configure port, JWT secret, relay server URL, and session limits.
