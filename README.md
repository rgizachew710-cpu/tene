# Tena Net Chapter Leaders & Their Activities

Professional activity tracker with administrator and viewer access.

## Setup

1. Copy `.env.example` to `.env.local` and set `ADMIN_CODE` and `SESSION_SECRET`.
2. Place your logo at `public/logo.png` (48×48 or larger, transparent background recommended).
3. Install and run:

```bash
npm install
npm run dev
```

Open [http://localhost:3000](http://localhost:3000).

## Administrator code

The administrator code is configured only in `ADMIN_CODE` on the server (`.env.local`). It is never embedded in the client bundle.

## Production

Set strong `SESSION_SECRET` and `ADMIN_CODE`, run `npm run build && npm start`, and serve over HTTPS so session cookies are secure.
