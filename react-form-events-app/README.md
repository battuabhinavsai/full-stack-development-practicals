# React Form Events

A small React application demonstrating controlled form inputs, component state with `useState`, and event handlers. The student form collects a name, age, gender, and branch; submitting displays the entered values, and **Clear** resets the form.

## Requirements

- Node.js and npm
- A modern web browser

## Getting started

From this directory, install the dependencies and start the Vite development server:

```bash
npm install
npm run dev
```

Open the local URL printed in the terminal.

## Available scripts

| Command | Description |
| --- | --- |
| `npm run dev` | Start the Vite development server |
| `npm run build` | Create a production build in `dist/` |
| `npm run preview` | Preview the production build locally |
| `npm run lint` | Run ESLint |

## Project structure

```text
src/
  App.jsx       Student form and event handlers
  App.css       Form styling
  index.css     Global styling
  main.jsx      React application entry point
index.html      Vite HTML entry point
```

## What you will learn

- Connect input values to React state.
- Handle change and submit events in a form.
- Reset form state after submission or when clearing the form.

## Follow the code

In `src/App.jsx`, follow each input's value and change handler, then inspect the submit and clear handlers.

## Try this next

Require a non-empty name and show a helpful message when the form is submitted without one.
