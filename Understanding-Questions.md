# Understanding Questions:

1. What are the steps of execution from the pressing of the 1 button to the rendering of our updated value? List what part of the code excutes for each step.

- The user presses the 1 button.
- ...

I believe the order of execution begins with the click and from there, it checks the dispatch function, sees whats in as its argument, in this case its the addOne() reducer and from there, it returns a copy of the state, and then adds one to the total of the state, updating the state each time addOne is called.

- TotalDisplay shows the total plus 1.
