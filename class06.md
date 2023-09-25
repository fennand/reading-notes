# Class 06 - Readings: Problem Domain, Objects, and the DOM

## Answers

### Javascript Object Basics

1. How would you describe an object to a non-technical friend you grew up with?

   - They are containers which have lists of related data in them.
  
2. What are some advantages to creating object literals?

   - Shorter syntax, it's more efficient than sending several items individually, and is easier when you want to identify individual items by name.
  
3. How do objects differ from arrays?

   - The data inside objects are known as properties which consists of a key and a value, whereas in arrays they are elements.
   - Objects handle strings better (things with properties), arrays are better for numbers (single variable data).
   - If you have to store the data in order or in a sequence then you should use an array, otherwise objects can be used for everything else.
  
4. Give an example for when you would need to use bracket notation to access an object’s property instead of dot notation.

   - If an object property name is held in a variable, then you can't use dot notation to access the value, but you can access the value using bracket notation.

5. Evaluate the code below. What does the term *this* refer to and what is the advantage to using *this*?

> const dog = {
  name: 'Spot',
  age: 2,
  color: 'white with black spots',
  humanAge: function (){
    console.log(`${this.name} is ${this.age*7} in human years`);
  }
}

   - *this* refers to all the data within the object, so in the example *this* is followed by *.name*, referring to the data in the identifier *name:* in the example object literal.
   - The advantage of using *this* is that it enables you to use the same method definition for every object you create, and it is essential when we start using constructors to create more than one object from a single object definition.

### Introduction To The DOM

1. What is the DOM?

   - The Document Object Model (DOM) is a programming interface for web documents. It represents the page so that programs can change the document structure, style, and content.
  
2. Briefly describe the relationship between the DOM and JavaScript.

   - Javascript is a programming language, and while the DOM is not, JS uses the DOM to access the document and its elements. Without the Dom, JavaScript wouldn't have any model or notion of web pages, HTML documents, SVG documents, and their component parts. 
