# Backend Development

Coursework repository containing backend laboratory experiments, web applications, database assignments, and supporting documentation.

## Backend Lab

| Item | Description | Documentation |
|---|---|---|
| CMS Lab | Express, EJS, MongoDB and CRUD content management system | [README](backend-lab/cms-lab/README.md) |
| Todo App | JWT-authenticated Todo API with MongoDB | [README](backend-lab/todo-app/README.md) |
| Experiment 03 | Responsive HTML and CSS page | [README](backend-lab/exp-03-responsive-page/README.md) |
| Experiment 05 | JavaScript arrays, objects and functions | [README](backend-lab/exp-05-javascript-basics/README.md) |
| Experiment 12A | Node.js, Express, Nodemon and EJS | [README](backend-lab/exp-12a-express-ejs/README.md) |
| Experiment 13 | MongoDB authentication with sessions and bcrypt | [README](backend-lab/exp-13-mongodb-auth/README.md) |
| Experiment 14 | Express application using PostgreSQL | [README](backend-lab/exp-14-postgresql/README.md) |

Complete index: [backend-lab/README.md](backend-lab/README.md)

## Backend Theory

| Assignment | Description | Documentation |
|---|---|---|
| Assignment 01 | Notes App using LocalStorage, JSON and CRUD operations | [README](backend-theory/Assignment%2001%20-%20Notes%20App/README.md) |
| Assignment 02 | PostgreSQL JSONB product catalog, queries and indexing | [README](backend-theory/Assignment%2002%20-%20PostgreSQL%20JSONB/README.md) |

Complete index: [backend-theory/README.md](backend-theory/README.md)

## Technologies Covered

HTML5, CSS3, JavaScript, Node.js, Express.js, EJS, MongoDB, Mongoose, PostgreSQL, JSONB, REST-style routing, CRUD operations, JWT, sessions, bcrypt and environment variables.

## General Setup

For browser projects, open the relevant `index.html`. For Node.js projects:

```bash
npm install
npm run dev
```

If a project has no development script, use the command specified in its README. Create `.env` from `.env.example` where provided. Never commit passwords, connection strings, API keys, `.env` files, `node_modules`, or database dumps.

## Repository Structure

```text
backend-development/
├── backend-lab/
│   ├── cms-lab/
│   ├── todo-app/
│   ├── exp-03-responsive-page/
│   ├── exp-05-javascript-basics/
│   ├── exp-12a-express-ejs/
│   ├── exp-13-mongodb-auth/
│   ├── exp-14-postgresql/
│   └── README.md
├── backend-theory/
│   ├── Assignment 01 - Notes App/
│   ├── Assignment 02 - PostgreSQL JSONB/
│   └── README.md
└── README.md
```

## Author

Prachi Menon
