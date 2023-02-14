# State and Props

## Reading
### [React Lifecycle](https://medium.com/@joshuablankenshipnola/react-component-lifecycle-events-cb77e670a093)
1. Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?
  - 'render' happens before 'componentDidMount'
2. What is the very first thing to happen in the lifecycle of React?
  - Mounting happens and constructor creation is the first thing to happen in Mounting.
3. Put the following things in the order that they happen: 'componentDidMount', 'render', 'constructor', 'componentWillUnmount', 'React Updates'
  - 'constructor', 'render, 'componentDidMount', 'React Updates', 'componentWillUnmount'
4. What does 'componentDidMount' do?
  - 'componentDidMount' is used for loading things or initializing the DOM.

## Video
### [React State vs Props](https://www.youtube.com/watch?v=IYvD9oBCuJI)
1. What types of things can you pass in the props?
  - Props are like arguments for functions so you could pass any variables or objects.
2. What is the big difference between props and state?
  - Props come from outside a component and are passed in, props cannot be changed within a component. State is within a component and cannot be passed back up but could be passed down to another component in the form of a prop.
3. When do we re-render our application?
  - When a state is changed or updated the application will re-render
4. What are some examples of things that we could store in state?
  - Things that will be changed or updated by the user should be stored in state.


