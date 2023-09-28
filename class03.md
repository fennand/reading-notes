# Class 03

## Readings: HTML Lists, Control Flow with JS, and the CSS Box Model

### Answers

#### Learn HTML - Ordered and Unordered lists

1. When should you use an unordered list in your HTML document?

   - When you want a bulleted collection of items that do not have a numerical ordering, and their order in the list is meaningless.

2. How do you change the bullet style of unordered list items?

   - Using the list-style-type property in CSS.
  
3.  When should you use an ordered list vs an unorder list in your HTML document?

   - When you want the order of your list to meaningful, like listing your favourite musical acts in a ranked order.

4. Describe two ways you can change the numbers on list items provided by an ordered list?

   - You could use the list-style-type properties of either a for lowercase letters, or I for uper case roman numerals for example.
  
#### Learn CSS - The Box Model

1. Describe the CSS properties of margin and padding as characters in a story. What is their role in a story titled: “The Box Model”?

   - In the story The Box Model, Padding is the princess in distress, stuck just on the inside of the border. No matter how big she makes herself, she cannot get passed this border. Margin in the hero prince, outside the border. There isn't a happy ending . . .
  
2. List and describe the four parts of an HTML elements box as referred to by the box model.

   - Content box. The box where the content is displayed, such as text or an image.
   - Padding box. Sits around the content as white space, the space between the content and the border.
   - Border box. Wraps content and padding, does exaclty what it says on the tin, it's a border.
   - Margin box. Wraps all the other elements. Creates white space outside of the border.
  
#### Learn JS - Arrays. Operators and Expressions. Conditionals. Loops.

1. What data types can you store inside of an Array?

   - They can store any data types, such as text, integers, booleans, other arrays, etc.
  
2. Is the people array a valid JavaScript array? If so, how can I access the values stored? If not, why?
 > const people = [['pete', 32, 'librarian', null], ['Smith', 40, 'accountant', 'fishing:hiking:rock_climbing'], ['bill', null, 'artist', null]];

   - Yes it is a valid array. To access the value of 'librarian', you would write people[0][1], and so on

3. List five shorthand operators for assignment in javascript and describe what they do.

   - Assignment - x = f() - This assigns a value to a variable or property.
   - Addition assignment - x += f() - This performs addition (which is either numeric addition or string concatenation) on the two operands and assigns the result to the left operand.
   - Remainder assignment - x %= f() - This performs remainder on the two operands and assigns the result to the left operand.
   - Exponential assignment - x **= f() - This performs exponentiation (the result of raising the first operand to the power of the second operand) on the two operands and assigns the result to the left operand.
   - Logical *AND* assignment - x &&= f() - This only evaluates the right operand and assigns to the left if the left operand is truthy.
  
4. Read the code below and evaluate the last expression and explain what the result would be and why.
>  let a = 10;
 let b = 'dog';
 let c = false;
 // evaluate this
 (a + c) + b;

   - The result would be 10dog. This is because when doing addition with a boolean it gets converted it to a number. As false = 0 and true = 1, the above is converted into 10 + 0 = 10. It would then concatenate the number to a string, so it is then 10dog.

5. Describe a real world example of when a conditional statement should be used in a JavaScript program.

  - Using an *if else* statement when getting input from a user. If you were designing a wesbite that featured gambling, you could use an *if else* statement to ask a user if they are older than 18. If they are not (falsey) you could then display a message stating they are not old enough to access the site and restrict when information is displayed.

6 . Give an example of when a Loop is useful in JavaScript.

  - If you had to print out a word or sentence multiple times on your screen, a loop would be a time saver.
