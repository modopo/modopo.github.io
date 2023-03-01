# Reading Class 02\3

React Docs - lists and keys

1) `.map()` returns a new array with each element being the result of the callback function.

2) You would use the `.map()` on the array and the callback function would return the value inside an element of some sort inside a new array as it "maps" through each value.

3) Each list item needs a unique key.

4) The purpose of the key is to help React identify which items have changed, are added, or are removed

Spread Operator

1) The spread operator allows any iterables be expanded. By expanded, the spread operator enumerates through the iterable, exapnding the arguments into a list of arguments to use in whatever function it's being invoked in.

2) Copy an array, Use Math functions on, Using an array as an argument, Adding to state in React

3) You add the flattened out array with the spread operator into the array you want to add it into as one of the item.

4) The same as above, you add the object with the spread operator into the object you want to add it to, separated by a comma.

Passing Functions between Components

1) You create the function where the state exist on.

2) The increment function increments the count based on a conditional when the name is the same.

3) You pass the method from parent to child with props.

4) The child component would invoke `this.props.yourFunctionPassedIn`.

## Things I want to know more about

How complex of a function can you pass down to the child?