# MyProject

A full-stack real estate listings app with user auth, listings management, and search. Backend runs on Express + MongoDB; frontend is a React (Vite) app with Tailwind and Redux.

## Features

- User auth (JWT + cookies)
- Create, update, delete listings
- Search and browse listings
- Client-side state with Redux Toolkit

## Tech Stack

- Backend: Node.js, Express, MongoDB (Mongoose)
- Frontend: React, Vite, Tailwind CSS, Redux Toolkit

## Getting Started

1. Install dependencies:

```
npm install
cd client && npm install
```

2. Configure MongoDB:

- Update the MongoDB connection string in `api/index.js`.

3. Run in development:

```
# terminal 1 (API)
npm run dev

# terminal 2 (client)
cd client && npm run dev
```

The API runs on `http://localhost:3000` and the Vite dev server runs on the port it prints in the terminal.

## Production Build

```
cd client && npm run build
npm start
```

The server will serve the built client from `client/dist`.
