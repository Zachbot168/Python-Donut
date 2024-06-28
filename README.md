Python Donut

In this program I use the libraries Pygame and math in order to generate a text rotating donut animation. I was able to learn and understand the much more intricate details and information about the math involved in coding as well as the utilization of libraries to make coding much more simpler

Mathematical Explaination

You may be asking how am I able to create a 3D animation on a 2D plane, so the math will be explained here. 

A Simple Explaination on Rendering

In more mathematical terms our donut is in the shape of a torus, it is rendered and animated through using a frame buffer and a z-buffer. In simple senses a frame buffer is essentially a data storing system which stores text frames in order to render images through text and animate them. A z-buffer simply is the same idea, however, it stores the depth, creating the perspective of 3D frame storage. To remove a lot of the processing power involved in rendering a complete full torus frame, we only place pixel, text, in places of fixed angles in close enough distances to create a torus. The z-bufering which renders the depth of an object determines the lighting level compared to our perspective and depending on the lighting level the text changes each frame going from lowest light level to highest light level, ".,-~:;=!*#$@". We can stores all these frames on python's Pygame library allowing the ability to render and animate a screen that shows the torus.
