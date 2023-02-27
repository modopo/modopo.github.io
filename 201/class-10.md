# Reading Class 10

Troubleshooting JS

1) Syntax errors are errors where the code is incorrectly written and the computer does not recognize what the commands are. Logical errors are where the syntax are all correct but the output/result are incorrect or deviated from the intended results.

2) Some errors I have encountered were syntax errors, where a method of an object required a callback function, but I passed an invoked function with () after the function. It both produced a logical error and syntax error because my callback function was invoked immediately and my output was just the callback function. I had to read the code and ask myself where was the function invoked at what point. I put logs before the callback function and after the callback function to see when the callback function was invoked.

3) Bugs are always going to happen, and it will just take practice to quickly figure out how to locate where the bug happened.

Debugger

1) The debugger is a tool that allows you to pause your code in real time to view what's happening to the code at the breakpoint you manually set. You're able to see exactly at the breakpoint what variables exist, what arguments are in the variables that exist and what functions are currently running.

2) A breakpoint is a place the user can set to pause when the code is being debugged. The code will execute to the breakpoint and wait until the user indicates to run further.

3) The call stack is the stack where it keeps track which code was executed to get to the line or breakpoint set.

## Things I want to know more about

The debugger tool in VSCode seems more robust than the one Chrome provides. I would like to understand in details how to fully utilize the debugger with any IDEs.
