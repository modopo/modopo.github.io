# Reading Class 37

Multiple Reducers Example

1) Creating multiple reducers in Redux provides a more organized, maintainable, scalable, and efficient approach to managing state in your application.

2) comebineReducers()

3) The state will be updated with a brand new state object instead of existing state directly.

Redux Docs: Using Combined Reducers

1) combineReducers is a utility function to simplify the most common use case when writing Redux reducers

2) The new state tree is assumebled by calling each slice reducers with its currenrt slice of state and the current action.

3) The intial state from is just the initial states from the individual reducuers.

Redux Docs: Combined Reducer Syntax

1) Having a centralized place to managed parts of the state is much easier to maintain.

2) The combineReducers helper function turns an object whose value are different reducing function into a single reducing function you can pass to createStore.

3) Name the reducers after the state slices it manages.