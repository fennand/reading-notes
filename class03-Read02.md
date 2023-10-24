# Class 301 - Read 02 - Readings: State and Props

## Answers

### React lifecycle

1. Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?

![React: Component Lifecycle Events](https://github.com/fennand/reading-notes/assets/99410959/d096cc7b-6b09-4122-b4fa-2f4c4250cd08)

   - Render will happen first, as the "Render phase" comes before the "Commit phase" in the lifecycle.

2. What is the very first thing to happen in the lifecycle of React?

   - The first phase is "Mounting", and the first thing to happen is the constructor for a component is called for.
  

3. Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates

   - Constructor, Render, React Updates, componentDidMount, and then componentWillUnmount.

4. What does componentDidMount do?

   - componentDidMount is invoked immediately after a component is mounted (inserted into the tree). It is the final step of the mounting process, using this we can execute the React code when the component has already been placed in the DOM. It is used for handling for all network requests and setting up subscriptions.
  
### React State Vs Props

1. What types of things can you pass in the props?

   - You can pass any JavaScript value through them, including objects, arrays, and functions.

2. What is the big difference between props and state?

   - Props are used to pass data from a parent component to a child component, while state is used to manage data within a component.

3. When do we re-render our application?

   - React re-renders components whenever their state or props change

4. What are some examples of things that we could store in state?

   - State can hold any kind of JavaScript value, including objects and arrays.
