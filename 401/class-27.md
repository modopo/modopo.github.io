# Reading Class 27

Thinking in React

1) Break the UI into a component hierarchy: Identify the components within the UI and arrange them in a hierarchy, with each component having a single responsibility.

2) Build a static version in React: Create a pure React version of the UI with hard-coded data to render the user interface. This version should have no interactivity.

3) Identify the minimal, but complete, representation of UI state: Determine the minimum set of states required to render the UI and make it interactive. Avoid duplicating data as much as possible.

4) Identify where your state should live: Place state in the parent component of all components that depend on it. If unrelated components need the same data, lift the state up to their closest common ancestor.

5) Add inverse data flow: Introduce callback functions to handle events, allowing the child components to update the state of their parent components.

State: A component's memory

1) A local variable isn't sufficient for managing a React component is because local variables only have a limited scope and lifetime within the component function where they are defined. Once the function is re-rendered, the variable is reset to its initial value.

2) The useState hook takes one argument which is the initial value of the state. It returns an array with two parts: the first part is the current value of the state, and the second part is a function that can be called to update the state.

3) Remove state from child components and add it to their closest shared parent