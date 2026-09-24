# CivicConnect repository files

This package is arranged for the `Grivence---orchestrator` repository:

- `frontend/` contains the finalized React/Vite CivicConnect application.
- `backend/` contains the current static Express production server used to serve the built frontend.

## Frontend

```bash
cd frontend
pnpm install
pnpm run build
```

The current demo stores login accounts, complaint updates, team members, report metrics, and settings in browser storage.

## Backend

The current `backend/index.ts` serves the compiled frontend and handles client-side routing. It does not yet provide a database, API authentication, email delivery, or server-side complaint persistence. Those should be added before production use.
Source code:https://github.com/Mownika57/Grivence---orchestrator/

## GitHub placement

Copy `frontend/` and `backend/` into the repository. If the repository already contains legacy files named `frontend` and `backend`, rename those legacy single files first (for example to `legacy-frontend.html` and `legacy-backend.py`) or place this package under a new directory such as `civicconnect-app/`.
