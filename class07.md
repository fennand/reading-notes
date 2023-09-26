# Class 07 - Readings: Object-Oriented Programming, HTML Tables

## Answers

### Domain Modelling

1. Explain why we need domain modeling.

   - We need it as it provides a visual repesentation of all the entities we are working with, helping us to digest what needs to be done.

### HTML Table Basics

1. Why should tables not be used for page layouts?

   - Layout tables reduce accessibility for visually impaired users. The output can be confusing to users.
   - They generally involve more complex markup structures than proper layout techniques. This can result in the code being harder to write, maintain, and debug.
   - Responsivity. Tables are not automatically responsive.
  
2. List and describe 3 different semantic HTML elements used in an HTML <table>.

   - < th > denotes the header of the table
   - < tr > denotes a row within the table
   - < td > denotes a cell (d = data)
  
### Introducing Constructors

1. What is a constructor and what are some advantages to using it?

   - A constructor is a special function that creates and initializes an object instance of a class. It gets called when an object is created using the new keyword, and its purpose is to create a new object and set values for any existing object properties. Advantages include:
     - More concise, d no need to repeat code as you would with mulitple object literals
     - It enables you to provide any custom initialization that must be done before any other methods can be called on an instantiated object.
     - When invoked with the new keyword, it assigns its prototype as the prototype of the returned object
    
2. How does the term *this* differ when used in an object literal versus when used in a constructor?

   - In an object literal, *this* refers to the current object the code is being written inside, and if you have more than one it enables you to use the same method definition for every object you create.
   - In a constructor,  *this* is bound to the new object being constructed, no matter which object the constructor function is accessed on. The value of *this* becomes the value of the *new* expression unless the constructor returns another non–primitive value.
  
### Object Prototypes Using A Constructor

1. Explain prototypes and inheritance via an analogy from your previous work experience.

   - I think it is a bit like when I had to raise the Breach paperwork in my previous job as a Probation Officer. A Breach is when an offender has not complied with their Order so the Probation Officer has to file a Breach of the Order with the Courts. In this example the Object is the standard Breach document, which has some already filled out information already. The child of this is when I then add any new or pertinent information that the Court may need to know, which is like adding a new feature, function, or new iteration.
