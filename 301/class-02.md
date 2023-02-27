# Reading Class 02

React lifecycle

1) Render happens first before "componentDidMount".

2) The very first thing that happens in the lifecycle of React is the constructor of any component is called before it is mounted. 

3) constructor(), render, React updates, componentDidMount, componentWillUnmount

4) The method componentDidMount() is invoked right after a component is mounted. If there is anything else needed to load with a network request or initialize in the DOM, this is where to set it up.

React State Vs Props

1) Any JavaScript value can be passed through props, such as objects, array and functions.

2) The big difference between state and props is props get passed to a component whereas state is managed within a componenet. In this sense, props are immutable, and states are mutable.

3) Rerendering happens when React needs to update the page with  new data. Usually, this happens as a result of a user interaction or some data comes through an request or some subscription model.

4) Some data that might be stored in a states are the current input data from the user, or the current index of the picture that needs to be rendered.

## Things I want to know more about

The syntax for React is something else I need to get used to. It seems similar to HTML when creating components, but not quite. Or, I have a complete incorrect understanding of React.