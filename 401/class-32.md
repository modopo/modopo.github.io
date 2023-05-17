# Reading Class 32

Scaling Up with Reducer and Context

1) `useReducer` and `useContext` are two hooks that work together to simplify state management in a React application. `useReducer` allows you to manage complex state in your application by dispatching actions to a reducer function, which then updates the state based on the action type and payload. This makes it easier to manage state that has multiple properties and requires complex updates. `useContext` allows you to access the state that is managed by `useReducer` from child components without having to pass props manually at every level. This is useful when you have state that needs to be shared across multiple components.