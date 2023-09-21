# Read: Class 04 - Readings: HTML Links, JS Functions, and Intro to CSS Layout

## Answers

### HTML

1. To create a basic link, we wrap text or other content inside what element?

   - An anchor tag < a >.
  
2. The href attribute contains what information?

   - The target, or web address.
  
3. What are some ways we can ensure links on our pages are accessible to all readers?

   - Including a < title >
   - Using good link text, helpful for screen readers
   - Using tab index, so users can tab to the links
   - Using access keys, so users can use a keyboard shortcut to get to the link
  
### CSS Layout

1. What is meant by “normal flow”?

   - Is the way that webpage elements lay themselves out if you haven't changed their layout.
  
2. What are a few differences between block-level and inline elements?

   - Block elements always start from a new line, inline elements never start from a new line.
   - Block elements have top and bottom margin, inline elements don't have a top and bottom margin.
   - Block elements cover space from left to right as far as it can go, inline elements only cover the space as bounded by the tags in the HTML element.
  
3. ___ positioning is the default for every html element.

   - Static
  
4. Name a few advantages to using absolute positioning on an element.

   - Allows elements to be positioned independently of their parent elements
   - Allows devs to precisely control the position of elements on a web page
   - Less dependence on margins and floats
  
5. What is a key difference between fixed positioning and absolute positioning?

   - Fixed positioning usually fixes an element in place relative to the visible portion of the viewport, and absolute positioning fixes an element in place relative to its nearest positioned ancestor (the initial containing block if there isn't one).
  
### Learn JS

1. Describe the difference between a function declaration and a function invocation.

   - A function declaration creates a Function object, and the function invocation is used to execute the code inside the curly braces in the function definition by adding () after function name after it has been defined to invoke that particular function.
  
2. What is the difference between a parameter and an argument?

   - A parameter is a variable in a function definition (t is a placeholder and hence does not have a concrete value), while an argument is a value passed during function invocation (therefore arguments can be said to fill in the place the parameters have held for them).
  
### Pair Programming

1. Pick 2 benefits to pair programming and reflect on how these benefits could help you on your coding journey.

   - Time/effort. Will be handy when you are struggling to complete a task on time, as a colleague would be able to access the code and help out.
   - Knowledge/expertise. When you are unable to move forward on project as you are stuck on something, someone with more knowledge could again take a look at the code and help.
