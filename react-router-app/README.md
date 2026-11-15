# React Router App

A small React application demonstrating client-side navigation with React Router. It includes Home, Contact, and Students pages, plus a parameterized student-details route.

## Requirements

- Node.js and npm

## Getting started

From this folder, install the dependencies and start the Vite development server:

```bash
npm install
npm run dev
```

Open the local URL printed by Vite in your browser.

## Routes

| Path | Page |
| --- | --- |
| `/` | Home |
| `/contact` | Contact |
| `/students` | Students |
| `/details/:id` | Student details for the specified ID |

## Available scripts

- `npm run dev` — start the development server
- `npm run build` — create a production build in `dist/`
- `npm run preview` — preview the production build
- `npm run lint` — run ESLint

## What you will learn

- Define client-side page routes with React Router.
- Navigate between pages without a full page reload.
- Read a route parameter to show the selected student's details.

## Follow the code

Inspect `src/App.jsx` for the route definitions, then follow the student link into `src/components/Students.jsx` and the parameter use in `Details.jsx`.

## Try this next

Show a not-found page for an unknown student ID and add a link back to the student list.
