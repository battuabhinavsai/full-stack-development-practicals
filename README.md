# Full-Stack Development Practicals

A collection of college practical projects for learning web development with JavaScript, React, Node.js, Express, and MongoDB. Each practical is kept in its own folder so you can study and run it independently.

> These are learning projects. Start with the early React examples, then move through the server and database examples, and finish with the full-stack app.

## Learning path

### 1. React foundations

| Order | Practical | What you will learn |
| --- | --- | --- |
| 1 | [HTML rendering](react-html-render-app/) | Mounting a React element into a page and rendering HTML-like JSX. |
| 2 | [JSX rendering](react-jsx-render-app/) | Writing JSX, using JavaScript values inside JSX, and composing a message. |
| 3 | [Nested components](react-nested-components-app/) | Splitting a page into reusable components and composing a page from them. |
| 4 | [Props and state](react-props-state-app/) | Passing data into components with props and changing interface state with `useState`. |
| 5 | [Rendering lists](react-rendering-lists-app/) | Turning an array into table rows with `map()` and assigning stable keys. |
| 6 | [State and events](react-state-events-app/) | Responding to clicks and updating the screen through state. |
| 7 | [Conditional rendering](react-conditional-rendering-app/) | Showing different content when a condition changes. |
| 8 | [Form events](react-form-events-app/) | Handling form input, submission, controlled values, and clearing a form. |
| 9 | [React Router](react-router-app/) | Building pages and navigating between them, including a route with an ID. |
| 10 | [Frontend CRUD expense tracker](react-frontend-crud-app/) | Adding, viewing, editing, and deleting records held in React state. |

### 2. Node.js and Express

| Order | Practical | What you will learn |
| --- | --- | --- |
| 11 | [Products file persistence](products-file-persistence-app/) | Creating Express routes and saving simple records to a JSON file. |
| 12 | [EJS template engine](template-engine-ejs-app/) | Rendering server-side pages and forms with EJS and organizing code with MVC. |
| 13 | [Express MVC movies API](mvc-express-app/) | Separating routes, controllers, and models while building JSON CRUD endpoints. |

### 3. MongoDB and full stack

| Order | Practical | What you will learn |
| --- | --- | --- |
| 14 | [MongoDB Express books API](mongodb-express-app/) | Connecting Express directly to MongoDB and building a REST API. |
| 15 | [Mongoose movies API](mongodb-mongoose-movies-app/) | Defining database models with Mongoose and querying MongoDB. |
| 16 | [MVC authentication API](mvc-auth-app/) | Structuring an API with MVC, hashing passwords, and protecting routes with JWTs. |
| 17 | [MERN CRUD app](mern-crud-app/) | Connecting a React interface to an Express API backed by MongoDB. |

## How to study each practical

1. Read the practical's README before opening the code.
2. Run the app and try its main feature.
3. Trace one action through the files. For example, follow a form submit to its React handler, API route, controller, and database operation.
4. Change one small thing, run it again, and explain what changed.
5. Try the README's next-step exercise before moving on.

Every project README includes its goal, concepts, important files or request flow, setup steps, and a small exercise. Some later projects require MongoDB; check their individual instructions first.

## Requirements

- Node.js and npm for JavaScript projects
- A modern web browser for React projects
- MongoDB for the database-backed projects; some projects include local Docker Compose instructions

Install and run commands are listed inside each practical folder. Run them from that folder, not from the repository root. The MERN project has separate `backend/` and `frontend/` instructions.

## Before sharing or running

- Do not commit a real `.env` file, password, database URI with credentials, or private token. The repository ignore file excludes `.env` files; keep `.env.example` files free of real secrets.
- Any sample database credentials in a local Docker Compose example are for learning on your own computer only. Replace them before using a hosted or production database.
- These practicals may use sample data and simplified error handling. Treat them as learning examples, not production-ready services.

## About

Created as college practical work to practice full-stack development concepts. The examples are organized as a learning path; project details and run instructions live in each folder's README.