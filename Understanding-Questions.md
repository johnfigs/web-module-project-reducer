# Understanding Questions:
1. What are the steps of execution from the pressing of the 1 button to the rendering of our updated value? List what part of the code executes for each step.
* The user presses the 1 button.
* the onClick handler attached the 1 button is fired.
* addOne function is called and returns the action type "ADD_ONE"
* dispatch is called with the value of "ADD_ONE"
* reducer is called with the current state, and the action type
* Case ADD_ONE is matched
* We pass through our current state, access the current total and add 1, this is our new state
* TotalDisplay shows the total plus 1.
