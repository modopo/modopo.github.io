# Reading Class 36

Redux Tutorials

1) The first principle of Redux is the single source of truth, where the entire state of the application is store in a single JS object in a Redux store.

2) In Redux, a store is a JavaScript object that holds the complete state tree of an application. It serves as the centralized data store, allowing components to access and update the state.

Reducers, on the other hand, are pure functions responsible for specifying how the state should be updated in response to dispatched actions. They take in the current state and an action as input and return a new state object, without mutating the original state. Reducers are registered with the store and are used by the store to determine how the state should be updated when actions are dispatched.

3) getState(): This method is used to retrieve the current state stored in the Redux store. It returns the current state object, allowing you to access and examine the data in your application.
dispatch(action): Used to trigger the state update in the Redux store by dispatching an action. The dispatched action is then processed by the reducers, which determine how the state should be updated.
subscribe(listener): Register a listener function that will be invoked whenever the state in the Redux store changes.

4) combineReducers combines all the reducers into a single main reducer, similarly like putting all the recipes into a binder, where it's centralized and organized. 