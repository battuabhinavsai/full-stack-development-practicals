# Express MVC Movies API

A small REST API for managing movies with Express and MongoDB through Mongoose. It demonstrates the Model–View–Controller pattern: routes map URLs to controller functions, controllers handle requests, and models describe database records.

## What you will learn

- Organize an Express application into routes, controllers, and models.
- Read JSON request bodies and URL/query parameters.
- Implement create, read, update, and delete (CRUD) operations.
- Connect to MongoDB with Mongoose and return JSON responses.
- Keep configuration in environment variables.

## Follow one request

For example, a request to list movies travels through `server.js`, which mounts `routes/movieRoutes.js`. The route calls a function in `controllers/movieController.js`, and that function queries the `Movie` model in `models/movieModel.js`.

## Run locally

Requirements: Node.js, npm, and a local or hosted MongoDB instance.

1. Install packages: `npm install`
2. Copy `.env.example` to `.env` and set `MONGO_URI` to your database connection string. Keep real credentials only in `.env`.
3. Start the API: `npm run dev` (or `npm start`)
4. The default port is `8000`. Send JSON requests to `http://localhost:8000/api/v1/movies`.

| Method | Path | Purpose |
| --- | --- | --- |
| `POST` | `/api/v1/movies` | Create a movie |
| `GET` | `/api/v1/movies` | List movies; optionally filter with `?category=...` |
| `GET` | `/api/v1/movies/:id` | Find one movie |
| `PUT` | `/api/v1/movies/:id` | Update a movie |
| `DELETE` | `/api/v1/movies/:id` | Delete a movie |

## Try this next

Add a route that filters movies by genre, then describe how its query parameter reaches the database query. The current list filter uses `category`, so you can adapt it or add a separate field.