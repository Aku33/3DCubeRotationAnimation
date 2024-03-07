3D Cube Rotation Animation
This project demonstrates a simple 3D cube rotation animation using JavaScript and the Three.js library. The animation is achieved by rotating a cube object along its X and Y axes.

Overview
The animation is implemented using the following steps:

Setting up the Scene: A Three.js scene is created to contain all the objects to be rendered.

Creating the Camera: A perspective camera is set up to define the view of the scene.

Creating the Renderer: A WebGL renderer is created to render the scene using hardware acceleration.

Creating the Cube: A cube geometry and material are defined, and then a mesh is created by combining them. This mesh represents the cube object.

Rendering Loop: A function is set up to continuously update and render the scene. Within this loop, the cube is rotated by a small amount along its X and Y axes, creating the animation effect.

How to Use
To use this project, follow these steps:

Include the Three.js library in your HTML file.
Include the index.js file containing the animation code.
Open the HTML file in a web browser.
Upon opening the HTML file in a browser, you should see a 3D cube rotating continuously.

Dependencies
This project relies on the Three.js library for 3D rendering.

Acknowledgements
Three.js: The project utilizes the Three.js library for 3D rendering capabilities.