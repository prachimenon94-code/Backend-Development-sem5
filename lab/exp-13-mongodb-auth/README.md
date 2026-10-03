# Experiment 13 — MongoDB Authentication

Express application demonstrating user registration and login with MongoDB, Mongoose, bcrypt password hashing, sessions and EJS views.

## Run

```bash
npm install
cp .env.example .env
npm run dev
```

On Windows, use `copy .env.example .env`. Start MongoDB before launching the application, then open `http://localhost:3001`.

## Security

Set the MongoDB URI, session secret and other values in `.env`. Do not commit `.env`.
