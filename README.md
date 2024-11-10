# nightCarSimulation
The goal of this computer graphics project is to simulate a scene of a car moving along a road at night under a starry sky with a full moon. The program creates a graphical representation using basic shapes and animation techniques.

Functionality of Different Functions:
1. main(): 
•	Initializes the graphics mode and necessary variables.
•	Creates the graphical environment and sets the screen size.
•	Executes the animation loop for moving the car.

2. initgraph(&gd, &gm, "X:\\TC\\BGI"):
•	Initializes the graphics system with the specified driver and mode.
•	&gd: Graphics driver.
•	&gm: Graphics mode.
•	"X:\\TC\\BGI": Path to the BGI driver files.

3. getmaxx() and getmaxy():
•	Retrieve the maximum pixel coordinates along the x-axis and y-axis, respectively.

4. cleardevice():
•	Clears the screen, preparing it for drawing new objects.

5. Drawing Stars:
•	Utilizes a loop to draw multiple stars at random positions within the upper half of the screen.
•	putpixel(x, y, WHITE): Draws a single white pixel representing a star.

6. Drawing Moon:
•	Draws a white circle representing the moon at a fixed position on the screen.
•	Utilizes circle() to draw the outline of the moon.
•	Utilizes floodfill() to fill the circle with white color.

7. Drawing Road:
•	Draws a white horizontal line to represent the road.

8. Drawing Car:
•	Draws a car moving horizontally across the screen.
•	Utilizes various line and arc functions to draw the car body and wheels.
•	Sets the color and fill style of the car.

9. delay(100):
•	Adds a delay of 100 milliseconds between successive frames, creating the illusion of motion.

10. closegraph():
•	Closes the graphics mode and deallocates memory associated with the graphics system.

These functions collectively create an animation of a car moving along a road at night, with stars twinkling in the sky and a full moon shining overhead.

![NightCar](https://github.com/user-attachments/assets/b6bf4e43-2b3c-4d94-a114-2a71fde164a3)

