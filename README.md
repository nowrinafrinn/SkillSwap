# SkillSwap

A peer-to-peer platform where people teach what they know and learn what they don't.

## Features

- Skill listings with search, reviews, and swap requests
- User profiles with ID verification
- Private messaging and notifications
- Community forum
- Map of users
- Admin dashboard

## Stack

Next.js, React, TypeScript, Tailwind CSS, Express, MongoDB (Mongoose), JWT, Leaflet

## Running locally

Backend: create `backend/.env` with `MONGODB_URI`, `JWT_SECRET`, `ADMIN_JWT_SECRET`, `ADMIN_USERNAME`, `ADMIN_PASSWORD`, and `IMGBB_KEY`, then:

```bash
cd backend
npm install
npm run dev
```

Frontend: create `frontend/.env.local` with `NEXT_PUBLIC_API_URL=http://localhost:5000` and `IMGBB_KEY`, then:

```bash
cd frontend
pnpm install
pnpm dev
```

## Credits

Built together with [sh00von](https://github.com/sh00von).
