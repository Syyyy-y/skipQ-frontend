# SkipQ frontend

React application for diner ordering, vendor fulfilment and sales. Payments and refunds are simulated.

[Backend repository](https://github.com/ICT381/ict381-2026-t02-tma-backend-Syyyy-y)

## Setup

Requires Node.js 22.12+, pnpm 11 and the backend running on port 5000. Follow the backend README to configure MongoDB and seed the database.

Run from the frontend folder:

```powershell
pnpm install --frozen-lockfile
pnpm dev
```

Open http://127.0.0.1:5173.

API requests are forwarded to http://127.0.0.1:5000. To change this, copy `.env.example` to `.env.local`, edit `API_PROXY_TARGET` and restart the frontend.

## Build and preview

```powershell
pnpm build
pnpm preview
```

Open http://127.0.0.1:4173. Keep the backend running.

## Demo accounts

All accounts use password **SkipQ-demo-2026!**.

| Email | Role |
| --- | --- |
| diner1@example.test | Diner |
| diner2@example.test | Second diner |
| vendor1@example.test | Rice Corner vendor |
| vendor2@example.test | Noodle House vendor |

Use separate browser profiles for diner and vendor. Signing in again with the same account replaces its previous token.

## Report and tests

Screenshots and architecture decisions are in report Q5. Q6 tests and execution instructions are in the backend repository.

## Lab provenance

Adapted from [myReactApp](https://github.com/ICT381/myReactApp). See report Q1b for the source-file mapping and adaptation rationale.

## Demonstration

Video link: [Video](https://github.com/ICT381/ict381-2026-t02-tma-backend-Syyyy-y/tree/main/q7-screencast)