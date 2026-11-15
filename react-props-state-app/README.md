# React Props and State Practical

A React example that displays student cards using props and an interactive counter using component state.

## What you will learn

- Pass data from a parent into a child through props.
- Destructure props in a component function.
- Use `useState` to remember a value and update the interface after a click.

## Follow the code

`src/App.jsx` passes names and ages to `Student`. `src/components/Student.jsx` displays them. `src/components/Counter.jsx` owns a count and updates it when its button is clicked.

## Run it

Requirements: Node.js and npm. In this folder run `npm install`, then `npm run dev`, and open the local address shown by Vite.

## Try this next

Add a decrement button. Then prevent the count from going below zero.