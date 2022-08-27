# React Docs 
--

## 1- What is the single responsibility principle and how does it apply to components?

 is a computer programming principle that states that "A module should be responsible to one, and only one, actor.The term actor refers to a group (consisting of one or more stakeholders or users) that requires a change in the module.


## 2- What does it mean to build a ‘static’ version of your application?

Static applications and websites render in the user’s browser without the need for server side processing, this means that all the rendering of HTML, CSS, and JavaScript is done on the client side, rather then relying on server side technologies. Whilst traditionally managing static websites and applications may seem like hard work, the medium has come on leaps and bounds over the past few years to the extent that it’s now perfectly feasible to run heavy content, rich media websites, and applications entirely in the browser – Good times!


## 3-Once you have a static application, what do you need to add?

we need to identify which component mutates, or owns, this state.



## 4-What are the three questions you can ask to determine if something is state?

1- Is it passed in from a parent via props? If so, it probably isn’t state.
2- Does it remain unchanged over time? If so, it probably isn’t state.
3- Can you compute it based on any other state or props in your component? If so, it isn’t state.

## 5-How can you identify where state needs to live?

1- Identify every component that renders something based on that state.
2- Find a common owner component (a single component above all the components that need the state in the hierarchy).
3- Either the common owner or another component higher up in the hierarchy should own the state.
4- If you can’t find a component where it makes sense to own the state, create a new component solely for holding the state and add it somewhere in the hierarchy above the common owner component.




--

# Higher-Order Functions



## 2-What is a “higher-order function”?


Functions that operate on other functions, either by taking them as arguments or by returning them, are called higher-order functions. Since we have already seen that functions are regular values, there is nothing particularly remarkable about the fact that such functions exist. The term comes from mathematics, where the distinction between functions and other values is taken more seriously.


## 2- Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?

 (Greater than): This operator compares one data item with another data item and validates whether it is greater than or not. If greater than condition satisfies, it returns “True” otherwise “False”.



 ## 3- Explain how either map or reduce operates, with regards to higher-order functions.


reduce function : It builds a value by repeatedly taking a single element from the array and combining it with the current value. When summing numbers, you’d start with the number zero and, for each element, add that to the sum.