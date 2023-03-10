# Reading Class 10

JavaScript Call Stack

1) A call is just a invocation of a function.

2) The calls can only happen one at a time.

3) LIFO is Last In, First Out, where the last one into the stack is the first one popped out.

4)
```
function fourthIn(){
  throw new Error('Stack Trace Error');
}

function thirdIn(){
  fourthIn();
}

function secondIn(){
  thirdIn();
}

firstIn();
```

5) Stack overflow happens when there's too many calls for the stack to handle, or there are calls made without an exit point.

JavaScript error messages

1) A reference error is when a variable that is not yet declared you get this type os errors.

2) Syntax error is when something is syntaxically incorrect and could not be parsed in terms of syntax.

3) Range error is when the range is beyond possibility for the object.

4) Type error is when the type is incompatible in the operation that's happening.

5) A breakpoint is where you can set a point in the code for the debugger to stop at and be on standy to inspect what the state of the code is currently at up to the breakpoint.

6) A debugger is a computer program to aide in testing and rooting out bugs/errors in other programs.

## Things I want to know more about