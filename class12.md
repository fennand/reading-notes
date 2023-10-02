# Read: Class 12 - Readings: Chart.js, Canvas

## Answers

### JavaScript Canvas

1. What does the < canvas > allow a developer to acheive?

   - It allows you to draw 2D graphics using JavaScript.
     
2. What is the importance of the closing `< /canvas > tag?

   - Any content between the opening and closing tags is fallback content that will display only if the browser doesn’t support the < canvas > element.
  
3. Explain what the getContext() method does.

   - It returns a render context object. This mehtod takes one argument which is the type of context. For example, you use the "2d" to get a 2D rendering context object, which is an instance of the CanvasRenderingContext2D interface. The 2D rendering context allows you to draw shapes, text, images, and other objects.
  
### Chart.js Documentation

1. What is Chart.js and how it can be brought into your project?

   - Chart.js is a free JavaScript library for making HTML-based charts, and it is one of the simplest visualization libraries for JavaScript.
   - To bring it in to your project, first you must add a link to the providing CDN (Content Delivery Network) in the Head of your document (similar to linking in your JS file). Then all you need to do is add the < canvas > element to where you want to draw the chart.
     
2. List 3 different Chart types you can create using Chart.js.

   - Scatter Plot
   - Bar Chart
   - Pie Chart
  
### Easily Create Stunning Animated Charts with Chart.js

1. What are some advantages to displaying data via a chart over a table?

   - They're easier to look at and better at conveying data quickly.
   - Charts are most useful when the data you are presenting is quantitative and has fewer distinct axes to measure. Also, they can show you the “shape” of data—patterns that emerge when the data is examined altogether instead of presented in sets of individual values.
     
2. How could Chart.js aid your previously created applications visually?

   - I can only think of one application we have made recently that involved displaying data in a table, and that is on the Salmon Cookies app. That would have been better to help visualise the results more clearly.
   - On the Odd Duck app we could possibly have used Chart'js to display that data in a chart instead of in a list, again this may have made it easier to interpret and more distinct/clear. 
