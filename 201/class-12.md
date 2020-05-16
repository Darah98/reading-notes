# Read12
## Mar 2, 2020 / Monday

### Chart.js

**It's easy to start:**

 All that's required is the script included in page along with a single < canvas > node to render the chart. 


**The < canvas > element has only two attributes, width and height, which are both *optional.* if width and height attributes are not specified, the canvas will initially be 300 pixels wide and 150 pixels high**

- It is always a good idea to supply an id because this makes it much easier to identify it in a script.
- Unlike the < img > element, the < canvas > element requires the closing tag (< / canvas >). 
- The < canvas > element has a method called getContext(), used to obtain the rendering context and its drawing functions. getContext() takes one parameter, the type of context.


### Checking for support
Some browsers dont know how to deal with canvas. 
- Scripts can also check for support programmatically by simply testing for the presence of the getContext() method.
- if (canvas.getContext) {

}

- **Drawing Shapes with *canvas***
- **Drawing Text with *canvas***
- **Applying Styles and Colors with *canvas***

### The grid

- pixels and grid units
- point of origin (0.0) top left corner



*That was very helpful! Go back to [Homepage](README.md)*