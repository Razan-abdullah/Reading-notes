
##class 03: 
###React Docs - lists and keys

1-What does .map() return?
Re It returns a new array and elements of arrays are result of callback function.

2-If I want to loop through an array and display each value in JSX, how do I do that in React?
The map() method is the most commonly used function to iterate over an array of data in JSX. You can attach the map() method to the array and pass a callback function that gets called for each iteration. When rendering the User component, pass a unique value to the key prop. 

3-Each list item needs a unique ____.
value to the key prop.

4-What is the purpose of a key?
The key prop helps React keep track of JSX elements and identify any changes in the array.





###The Spread Operator

1-What is the spread operator?

The spread operator is a feature of JavaScript introduced with ES6 that gives you access to the insides of an iterable object. An “iterable object” is anything you can iterate over item by item, such as arrays, objects literals, and strings. These kinds of JavaScript types can be traversed in some sequential fashion. For example, you can use a for loop on an array, or with JavaScript objects, you can use for...in loops.


2-List 4 things that the spread operator can do.

Copying an array.
Concatenating or combining arrays.
Using Math functions.
Using an array as arguments.
Adding an item to a list.
Adding to state in React.



3-Give an example of using the spread operator to combine two arrays.

const cars = ['🚗', '🚙'];
const trucks = ['🚚', '🚛'];

/ Method : Spread
const combined2 = [...cars, ...trucks];
// Result
// [ '🚗', '🚙', '🚚', '🚛' ]


4-Give an example of using the spread operator to add a new item to an array.
function sum(x, y, z) {
  return x + y + z;
}

const numbers = [1, 2, 3];

console.log(sum(...numbers));
// expected output: 6

console.log(sum.apply(null, numbers));
// expected output: 6




5-Give an example of using the spread operator to combine two objects into one.

let person = {
    firstName: 'John',
    lastName: 'Doe',
    age: 25,
    ssn: '123-456-2356'
};


let job = {
    jobTitle: 'JavaScript Developer',
    location: 'USA'
};

let employee = {
    ...person,
    ...job
};

console.log(employee);

###How to Pass Functions Between Components:
In the video, what is the first step that the developer does to pass functions between components?
creat a function thin pass the object 
In your own words, what does the increment function do?
How can you pass a method from a parent component into a child component?
How does the child component invoke a method that was passed to it from a parent component?

