# React State and Events

A small React application demonstrating component state and event handling. The page starts with a red background; selecting **Blue**, **Green**, or **Yellow** updates the background color using React's `useState` hook.

## Requirements

- Node.js and npm
- A modern web browser

## Getting started

From this directory, install dependencies and start the Vite development server:

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
  App.jsx       Interactive background-color example
  main.jsx      React application entry point
  App.css       Component styles
  index.css     Global styles
index.html      Vite HTML entry point
```

## What you will learn

- Store a chosen color in React state.
- Connect button click handlers to state updates.
- Use state to change the page appearance.

## Follow the code

In `src/App.jsx`, inspect the state value, the color buttons, and where the selected color is used in the rendered page.

## Try this next

Add a reset button that restores the original color, then display the selected color name on the page.
