1. IN BOB.JS:
instead of ellipseMode(radius) using ellipseMode(center)-The default mode (CENTER) uses the first two parameters as the center,The RADIUS mode is the same, except that the last two parameters specify the radius instead of the diameter. 

2.why offset?
The . offset() method allows us to retrieve the current position of an element (specifically its border box, which excludes margins) 

The Matter.Render module is a simple HTML5 canvas based renderer for visualising instances of Matter.Engine. It is intended for development and debugging purposes, but may also be suitable for simple games. It includes a number of drawing options including wireframe, vector with support for sprites and viewports.

more info: https://brm.io/matter-js/docs/classes/Render.html