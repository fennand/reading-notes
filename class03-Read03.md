# Class 301 - Read 03 - Readings: Passing Functions as Props

## Answers

### React Docs - lists and keys

1. What does .map() return?

   - The .map() method allows you to run a function on each item in the array, returning a new array as the result.

2. If I want to loop through an array and display each value in JSX, how do I do that in React?

   -
   
3. Each list item needs a unique ____.

   - Key prop.

4. What is the purpose of a key?

   - Keys help React identify which items have changed, are added, or are removed.
  
### The Spread Operator

1. What is the spread operator?

   - The JavaScript spread operator is a toll that allows us to quickly copy all or part of an existing array or object into another array or object. 

2. List 4 things that the spread operator can do.

   - It can make a shallow copy of an array.
   - It can concatenate an array to the end of an existing array.
   - It can conditionally add values to an array.
   - It can merge multiple objects into one new object

3. Give an example of using the spread operator to combine two arrays.

   - > let arr1 = [0, 1, 2];
     > const arr2 = [3, 4, 5];

     > arr1 = [...arr1, ...arr2];

4. Give an example of using the spread operator to add a new item to an array.

   -
   
5. Give an example of using the spread operator to combine two objects into one.

   -

### How to Pass Functions Between Components

1. In the video, what is the first step that the developer does to pass functions between components?

   -
   
2. In your own words, what does the increment function do?

   -
   
3. How can you pass a method from a parent component into a child component?

   -
   
4. How does the child component invoke a method that was passed to it from a parent component?

   -
