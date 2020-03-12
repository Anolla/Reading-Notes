# HTML <canvas> Element & Chart.js

## CREATE ANIMATED CHARTS WITH CHART.JS

- Drawing a line chart
- Drawing a pie chart
- Drawing a bar chart

\<canvas id="tutorial" width="150" height="150"></canvas>

- the \<canvas> element has only two attributes, width and height. These are both optional and can also be set using DOM properties. When no width and height attributes are specified, the canvas will initially be 300 pixels wide and 150 pixels high.

- It is always a good idea to supply an id because this makes it much easier to identify it in a script.

- The \<canvas> element can be styled just like any normal image (margin, border, background…)

- As a consequence of the way fallback is provided, unlike the <img> element, the \<canvas> element requires the closing tag (</canvas>). If this tag is not present, the rest of the document would be considered the fallback content and wouldn't be displayed.

- The canvas is initially blank. To display something, a script first needs to access the rendering context and draw on it. The <canvas> element has a method called getContext(), used to obtain the rendering context and its drawing functions. getContext() takes one parameter, the type of context. For 2D graphics, such as those covered by this tutorial, you specify "2d" to get a CanvasRenderingContext2D.

