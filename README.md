# Midpoint Circle Drawing Algorithm with OpenGL

This program implements the Midpoint Circle Drawing Algorithm using OpenGL. It draws a circle on a Cartesian plane, allowing the user to input the radius. The resulting circle is displayed along with a grid, and Cartesian coordinates.

## Features:

- **Midpoint Circle Drawing Algorithm**: The algorithm is used to calculate the pixel coordinates of the circle in the first octant, and these points are then mirrored to complete the circle.

- **OpenGL Visualization**: The circle and other elements are visualized using OpenGL.

- **User Interaction**: Users can input the radius of the circle, and the program will display the circle accordingly.

- **Grid and Cartesian Coordinates**: The program also displays a grid and Cartesian coordinates to provide a reference.

- **Square and Axes**: A square and axes are included for additional illustration.

## How to Use:

1. **Compile the Code**: Use a C++ compiler to compile the code. Ensure that you have the necessary OpenGL libraries installed.

```bash
g++ -o CircleDrawing circle_drawing.cpp -lGL -lGLU -lglut
```

2. **Run the Executable**:

```bash
./CircleDrawing
```

3. **Enter Radius**: The program will prompt you to enter the radius. Input a value from -10 to +10.

4. **View the Result**: The OpenGL window will display the circle, grid, Cartesian coordinates, square, and axes.

## Note:

- The program uses the Midpoint Circle Drawing Algorithm to calculate the pixel coordinates of the circle.
