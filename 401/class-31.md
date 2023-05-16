# Reading Class 31

Choosing the State Structure

1) i: identify the single source of truth. ii: determine what should be stored in the state. iii: encapsulate related state. iv: identify state ownership. v: avoid over-nesting and prop drilling

Passing State Deeply with Context

1) Context tries to solve prop drilling by providing a more efficient way to share and access data across components in a React app.

2) Before useContext or other advanced state management techniques, try to evaluate if the application can benefit from a more carefully designed component structure that minimizes prop drilling by lifting state up to the nearest common ancestor component.

3) useReducer, and useContext