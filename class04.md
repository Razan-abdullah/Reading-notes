# React Docs - Forms
-

### 1- What is a ‘Controlled Component’?
Controlled Components: In React, Controlled Components are those in which form’s data is handled by the component’s state. It takes its current value through props and makes changes through callbacks like onClick, onChange, etc. A parent component manages its own state and passes the new values as props to the controlled component.


### 2-Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.

we should update the state. to keep it sync with the input’s value, meaning that changing the input will update the state, and updating the state will change the input.


### 3- How do we target what the user is entering if we have an event handler on an input field?

The change event triggers when the element has finished changing.

For text inputs that means that the event occurs when it loses focus.

For instance, while we are typing in the text field below – there’s no event. But when we move the focus somewhere else, for instance, click on a button – there will be a change even

--

# The Conditional (Ternary) Operator Explained


### 1- Why would we use a ternary operator?


to shorten our if statements into one line of code with the conditional operator.

### 2- Rewrite the following statement using a ternary statement:

>`if(x===y){`  
>   `console.log(true);`  
>`} else {`  
>   `console.log(false);`  
>`}`  

`(x === y) ? console.log(true) : console.log(false)`

---

Thigs I want to know: 
---------

