# Understanding Questions:
1. What are the steps of execution from the pressing of the 1 button to the rendering of our updated value? List what part of the code excutes for each step.
* The user presses the 1 button.
* The OnClick user event fires
* The dispatch is called and it sends the addOne function to othe reducer
* The addOne function returns to the reducer the case of ADD_ONE
*The reducer matches the case and returns back an entire object changing only the matched key...
*Exchanging it for the state.total + 1
*The app rerenders showing the updated total in the operation span
...

* TotalDisplay shows the total plus 1.
