# Class 11

## Readings: Audio, Video, Images

### Answers

#### Video and Audio Content

1. Explain how the ability to use video and audio on the web has evolved since the early 2000s.

   - The first influx of online videos and audio were made possible by proprietary plugin-based technologies like Flash and Silverlight. Both of these had security and accessibility issues, and are now obsolete, in favor of native HTML solutions <video> and <audio> elements and the availability of JavaScript APIs for controlling them.
  
2. Describe the use of the src and controls attributes in the <video> element.

   - Src contains a path to the video you want to embed, and works the same way as when used with an image.
   - Controls includes the browsers control interface, so users can control playback.
   
3. Why is it important to have fallback content inside the <video> element?

   - This is important if the browser accessing the page doesn't support the <video> element, allowing us to provide a fallback for older browsers.
     
4. Write a very short story where <audio> and <video> are characters.

   - There once was a fiefdom where chaos ruled and order was sought. Along came two heroes, Audio (with his trumpet of truth) and Video (with her sword made of pure light). With them came a series attributes and properties, which helped make bring order and sense to all the characters around them, bringing happiness to the people and an end to this *story*.

#### A Complete Guide To Grid

1. How does Grid layout differ from Flex?

   - Flex layout is designed for layout in one dimension - either a row or a column. Grid was designed for two-dimensional layout - rows, and columns at the same time.
  
2. Grid container, grid item, and grid line are a few important terms to understand when using Grid. Please describe these terms in a few sentences.

   - Grid container is the element on which display: grid is applied. It’s the direct parent of all the grid items.
   - Grid items are the children (i.e. direct descendants) of the grid container.
   - Grid lines are the dividing lines that make up the structure of the grid. They can be either vertical (“column grid lines”) or horizontal (“row grid lines”) and reside on either side of a row or column.

#### Responsive Images

1. Besides making a site visually appealing across different screen sizes, why should developers make images responsive?

   - Because it also helps to improve performance across different devices.
     
2. Define the following <img> attributes srcset and sizes. Write an example of how they are used.

   - Srcset and sizes are used to provide several additional source images along with hints to help the browser pick the right one.
  
   Example

> < img srcset="andy-480w.jpg 480w, andy-800w.jpg 800w" sizes="(max-width: 600px) 480px, 800px"

  - In this example we have given the browser two images to choose from, with the image filename followed by the intrinsic width in pixels.
  - Then we have a media condition (max-width:600px) followed by the width of the slot the image will fill when the media condition is true (480px).
  - So in this instance the browser will Look at its device width, work out which media condition in the sizes list is the first one to be true, look at the slot size given to that media query, and then load the image referenced in the srcset list that has the same size as the slot or, if there isn't one, the first image that is bigger than the chosen slot size.

3. How is srcset more helpful for responsive images than CSS or JavaScript?

   - It is more helpful as the affect if srcset takes place as soon as the page is loaded, whereas CSS and Javascript only come into affect once the main parser has loaded.
