# Reading Class 05

React Docs - Thinking in React

1) Single responsibility principle is the principle that a componenet should ideally only do one thing.

2) Building a static version of the app means componenets reuse other components and assuming all data is coming from props with no state at all.

3) Once the static version of the app is built, the state needs to be added for interactivity.

4) Is it passed from parents via props? Does it remain unchanged over time? Is it computed from any other state or props in the component?

5) Find all the components that render based off the same state. Find the common component that needs the state in the heirarchy. That component or higher up should own the state. If it doesn't make any sense for a component to own the state, create a component for the sole purpose of keeping the state and place it one up above the common owner component.

Higher-Order Functions

1) Functions that operate on other functions as either arguments or by return them are higher-order functions.

2) Line 2 is returning a function that would compare the number that was passed in initially

3) `map` uses another function on all the elements and builds a new array with the transformed values. Since it operates on another function, `map` itself is the higher-order function

## Things I want to know more about

Thinking in React was a good article. I would like to practice more on this school of methodology the article writes about.