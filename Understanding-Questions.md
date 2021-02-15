# Understanding Questions:
1. What are the steps of execution from the pressing of the 1 button to the rendering of our updated value? List what part of the code excutes for each step.
* The user presses the 1 button.
* 1. Add 1 comes from state
* 2. State comes from initialState found in reducer. From the initialState, Total is used in the reducer function.
* 3. The instance of ADD_ONE comes from the addOne function in the actions file.
* 4. What happens in the reducer function is that the initial state is copied and the new state adds one. 
* 5. Then the addOne function is imported into the App component
* 6. THen in the App component a dispatch is sent on the handleClick, which rerenders the total
...

* TotalDisplay shows the total plus 1.
