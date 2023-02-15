# Passing Functions as Props

### Today's readings and videos addressed how to pass functions as props as well as how to use map() to create lists with react.
### Spread operators are helpful in a multitude of ways like combining or adding to arrays.

## Readings
### [React Docs - lists and keys](https://reactjs.org/docs/lists-and-keys.html)
1. What does .map() return?
  - it returns the results of a function that acts on each piece of the array.
2. If I want to loop through an array and display each value in JSX, how do I do that in React?
  - create a new array with .map() that consists of the numbers nest in an html element.
3. Each list item needs a unique ____.
  - Key
4. What is the purpose of a key?
  - They help track elements inside of an array.

### [The Spread Operator](https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab)
1. What is the spread operator?
  - '...'
2. List 4 things that the spread operator can do.
~~~
  - spread an array into seperate arguments for a function,
  - Copying an array
  - Concatenating or combining arrays
  - Using Math functions
  - Using an array as arguments
  - Adding an item to a list
  - Adding to state in React
  - Combining objects
  - Converting NodeList to an array
~~~
  - (copied from reading)
3. Give an example of using the spread operator to combine two arrays.

~~~ js
const hello = {hello: "😋😛😜🤪😝"}
const world = {world: "🙂🙃😉😊😇🥰😍🤩!"}
const helloWorld = {...hello,...world}
console.log(helloWorld) // Object { hello: "😋😛😜🤪😝", world: "🙂🙃😉😊😇🥰😍🤩!" }
~~~
  - (copied from reading)

4. Give an example of using the spread operator to add a new item to an array.
~~~ js
const fewFruit = ['🍏','🍊','🍌']
const fewMoreFruit = ['🍉', '🍍', ...fewFruit]
console.log(fewMoreFruit) //  Array(5) [ "🍉", "🍍", "🍏", "🍊", "🍌" ]
~~~
  - (copied from reading)
6. Give an example of using the spread operator to combine two objects into one.
~~~ js
const firstName = { first: 'Ethan' }
const lastName = { last: 'Albers' }
const fullName = { ...firstName, ...lastName }
console.log(fullName) // Object { first: 'Ethan', last: 'Albers' }
~~~
  
## Video
### [How to Pass Functions Between Components](https://www.youtube.com/watch?v=c05OL7XbwXU)
1. In the video, what is the first step that the developer does to pass functions between components?
  - Creates an increment() function
2. In your own words, what does the increment function do?
  - it creates a new array with an updated count of +1 for the name passed as the argument then uses .setState() to update the state of the array to match the array created.
3. How can you pass a method from a parent component into a child component?
  - by including it as a prop.
4. How does the child component invoke a method that was passed to it from a parent component?
  - by calling it the same way you would call any other prop, this.prop.function().

## Things I want to know more about:
### 
