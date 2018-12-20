# SUVAT-Calculator-Graph
This mini project was coded while I was learning about the SUVAT equations in both my Physics and Mechanics classes. The coding was one in Visual Studio Code on my Macbook Pro, using the python language with the extension MatPlotLib.
There are three subroutines, the Input, the Calculating, and the Graphing

**_Input Section_**
Asks the user for the horizontal and vertical components, this includes: displacement(m),initial velocity(m/s),final velocity(m/s),acceleration(m/s^2),time(s).
The only validation included is checking that enough values are inputted for an actual calculation, and that only numbers are inputted(integer or float).

**_Calcuating Section_**
Uses these 5 equations (where s = displacement, u = initial velocity, v = final velocity, a = acceleration, t = time):
v = u + at    |   s = (u+v) * 1/2 * t   |   v^2 = u^2 + 2 * as    |   s = ut + 1/2 * at^2   |   s = vt - 1/2 * at^1/2

Each of these equations are rearranged to make every component the subject so that given at least 3 components, all the other values can be calculated.
These are SUVAT equations, so *constant acceleration is a requirement*.

**_Graphing Section_**
6 Graphs are created, 3 for horizontal components, and 3 for vertical components. For each the 3 graphs made are: Displacement time graphs, Velocity time graphs, and Acceleration time graphs
For all of the graphs, the x axis is time, represented by an array starting from 0, incrementing by 0.1. The y axis is calculated and added to the list to line up with the x axis, both lists are then put into matplotlib to produce the six graphs.
