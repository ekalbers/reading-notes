# Putting it all together

  - These readings help us to understand the most optimal way for structuring our apps as well as exploring higher-order functions to help us understand how certain functions work and the benefits of writing functions that way.

## Readings
### [React Docs - Thinking in React]([HTML](https://reactjs.org/docs/thinking-in-react.html))
1. What is the `single responsibility principle` and how does it apply to components?
  - Using something for only one purpose. For components this ideally means that you only use the component for one thing and if it grows into doing more than that, you should split it off into a different component.
2. What does it mean to build a ‘static’ version of your application?
  - Building a versio that displays all of the data but has no interactivity.
3. Once you have a static application, what do you need to add?
  - interactivity
4. What are the three questions you can ask to determine if something is state?
> 1. Is it passed in from a parent via props? If so, it probably isn’t state.
> 2. Does it remain unchanged over time? If so, it probably isn’t state.
> 3. an you compute it based on any other state or props in your component? If so, it isn’t state.
  - (copied from reading, Section: Step 3: Identify The Minimal (but complete) Representation Of UI State)
5. How can you identify where state needs to live?
  - By identifying all the components that need the state, then put the state in a common parent of all those components.

### [Higher-Order Functions]([HTML](https://eloquentjavascript.net/05_higher_order.html#h_xxCc98lOBK))
1. What is a "higher-order function"?
> Functions that operate on other functions, either by taking them as arguments or by returning them, are called higher-order functions.
  - (copied from reading, Section: Higher-Order Functions, first sentence)
2. Explore the `greaterThan` function as defined in the reading. In your own words, what is line 2 of this function doing?
  - It is returning a function to test if a number is greater than the number `n` passed to `greaterThan(n)`.
3. 1. Explain how either `map` or `reduce` operates, with regards to higher-order functions.
  - map creates a new array by applying a given function to every value within the array being mapped.

### Things I want to know more about:
  - I would like to understand more about higher-order functions. I think I understand but the last question made me question it a little bit becuase I wasn't sure how to explaine it 'with regards to higher-order functions'
