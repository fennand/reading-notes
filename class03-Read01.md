# Class 301 - Read 01 - Readings: Introduction to React and Components

## Answers

### Component-Based Architecture

1. What is a “component”?

   - Components are independent and reusable bits of code. They serve the same purpose as JavaScript functions, but work in isolation and return HTML.

2. What are the characteristics of a component?

   - Reusability − Components are usually designed to be reused in different situations in different applications. However, some components may be designed for a specific task.
   - Replaceable − Components may be freely substituted with other similar components.
   - Not context specific − Components are designed to operate in different environments and contexts.
   - Extensible − A component can be extended from existing components to provide new behavior.
   - Encapsulated − A component depicts the interfaces, which allow the caller to use its functionality, and do not expose details of the internal processes or any internal variables or state.
   - Independent − Components are designed to have minimal dependencies on other components.

3. What are the advantages of using component-based architecture?

   - Ease of development − Components implement well-known interfaces to provide defined functionality, allowing development without impacting other parts of the system.
   - Reusable − The use of reusable components means that they can be used to spread the development and maintenance cost across several applications or systems.
   - Modification of technical complexity − A component modifies the complexity through the use of a component container and its services.
   - Reliability − The overall system reliability increases since the reliability of each individual component enhances the reliability of the whole system via reuse.
   - System maintenance and evolution − Easy to change and update the implementation without affecting the rest of the system.
   - Independent − Independency and flexible connectivity of components. Independent development of components by different group in parallel. Productivity for the software development and future software development.

### What is Props and How to Use it in React

1. What is “props” short for?

   - It is a special keyword in React, which stands for properties. It is used for passing data from one component to another in an uni-directional flow (one way from parent to child).

2. How are props used in React?

   - Props are used to store data that can be accessed by the children of a React component. They take the place of class attributes.

3. What is the flow of props?

   - 
