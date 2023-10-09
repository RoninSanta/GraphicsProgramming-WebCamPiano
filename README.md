# Graphics Programming-WebCam Piano
It is a demo created by using the camera capture feature of the p5 library and try to make something creative with it.
- It is able to play sound with the motion it detected from the camera

### [Instructions]
This is a built using the p5.js library so therefore make sure that the p5 library is installed on your IDE(Visual Studio Code, etc..) before running the project. For VSCode users make sure to install the 'live-server' extension and right click the **index.html** file and choose the `Open with Live Server` option and the game will run on a HTML window on your browser. 

### The app requires camera access in order to work 
Using the video capture, I used the background subtraction method to find the differences between 2 images and therefore able to capture any movemnet detected.

- The movement is classifies as shapes(I choose circle) and the circles are colored by the speed of movement
- Different size, color is assigned diff sound notes
- The project works similar to a `theremin` as you need to move differently to produce diff sounds
