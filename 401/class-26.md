# Reading Class 26

React Quick Start

1) React apps are made out of components. A component is a piece of the UI (user interface) that has its own logic and appearance. A component can be as small as a button, or as large as an entire page.

2) HTML elements are static and defined by markup, while React components are programmatically defined and can be customized with dynamic data and logic.

3) JSX is a syntax extension for JavaScript that allows developers to write HTML-like code to define the structure and content of React components, making it easier to read and write complex UI code.

4) JavaScript expressions can be embedded in JSX by wrapping them in curly braces, allowing them to be evaluated and their values rendered as part of the component's output.

5) React has built-in features such as the map() method and conditional rendering using the ternary operator or the logical && operator to handle iteration and conditional logic within JSX expressions.

6) React responds to a user's inputs by attaching event listeners to the relevant DOM elements and updating the component's state or triggering callbacks as needed.

7) React component manages data with a Hook is with "useState".

8) Two React components can share data by passing props from a parent component to its child components.

Render and Commit

1) Trigger a render, React renders conmponents, and finally commiting the changes to the DOM

2) setState() method is used to update the component's state, which will in turn trigger a re-render of the component and its children with the updated state values.

3) No, React will apply the minimal necessary operations to make the DOM match the latest rendering output.

4) the browser still needs to perform layout and painting to render the updated content on the screen, which can take a few milliseconds