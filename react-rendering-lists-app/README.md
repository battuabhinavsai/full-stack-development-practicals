# React List Rendering App

A small React application that demonstrates rendering a list of patient records in a table. Each row is generated from an array using JavaScript's `map()`.

## Requirements

- Node.js and npm

## Getting started

From this folder, install the dependencies and start the Vite development server:

```bash
npm install
npm run dev
```

Open the local URL printed by Vite in your browser.

## Available scripts

- `npm run dev` — start the development server
- `npm run build` — create a production build in `dist/`
- `npm run preview` — preview the production build
- `npm run lint` — run ESLint

## What you will learn

- Store repeated records as JavaScript objects in an array.
- Use `map()` to create a table row for each object.
- Use a stable key so React can track each row.

## Follow the code

In `src/App.jsx`, compare the `patients` array fields with the table headers and the values rendered for each row.

## Try this next

Add a button that filters the list to one ward, then render a friendly message when no records match.
