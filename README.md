# Chai Order System

Café / Chai POS with billing, tables, QR ordering, waiter app, reports.
Node.js (no Express) + MySQL backend, React frontend (pre-built in `frontend/build`).

## Local run
1. `npm install`
2. Copy `backend-node/.env.example` to `backend-node/.env` and fill values
3. `npm start` -> http://localhost:5000

Tables are created automatically on first start (migration runs in `server.js`).

## Rebuild frontend (only if you change `frontend/src`)
    cd frontend && npm install && npm run build
Then commit the updated `frontend/build`.
