# Reading Class 29

Extracting State Logic into a Reducer

1) A reducer helps manage the pieces of information or data in your application, ensuring they are organized, changes are tracked, and mistakes can be easily fixed.

2) By using actions and a reducer, you can provide a clear intent of the change you want to make without directly manipulating the state. The reducer, which is a function specifically designed to handle these actions, receives the current state and the action as inputs. It then produces a new state based on the specified action and returns it.

3) The useReducer hook is named after the list operation called "reduce". The hook enables the accumulation and transformation of state based on actions, mirroring the behavior of reducers in functional programming and state management.

4) Use a reducer if you often encounter bugs due to incorrect state updates in some component, and want to introduce more structure to its code.