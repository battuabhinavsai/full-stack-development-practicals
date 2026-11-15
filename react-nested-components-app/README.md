# React Nested Components Practical

A React page composed from smaller reusable components: a header, student cards, and a footer.

## What you will learn

- How to define a component in its own file and import it.
- How a parent component combines child components.
- How props let one component display different data for different students.

## Follow the code

`src/App.jsx` lays out the page and renders `Header`, several `Student` cards, and `Footer`. Each `Student` receives a different `name` and `age`.

## Run it

Requirements: Node.js and npm. In this folder run `npm install`, then `npm run dev`, and open the local address shown by Vite.

## Try this next

Put the student records in an array and render the cards with `map()`. Add a unique `key` to each card.