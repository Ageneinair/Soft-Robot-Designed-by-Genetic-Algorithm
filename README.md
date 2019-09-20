# Soft-Robot-Designed-by-Genetic-Algorithm

This repo is a genetic algorithm to generated the motion strategy and morphology of the soft robot automatically to make this soft robot move more efficiently.

## Physical Environment Validation
The physical environment is visualized by C++ OpenGL. We let an elastic cube drop from a certain height and to see if it performs like real world.
Here is the result, and **click** below image you can see the result video.
[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/_9c0Z--fuME/0.jpg)](https://www.youtube.com/watch?v=_9c0Z--fuME)

## Motion Learning of the robot
Our robot is shaped as a cube. And all 28 springs, which are connecting every pairs of masses, satisfied a variational rest length equation.
The algorithm will evolve the cube rest length equation generation by generation. And along with the evolution, we can see the cube runing faster and faster.

Here is the result, and **click** below image you can see the result video.
[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/4de_eXFRPHQ/0.jpg)](https://www.youtube.com/watch?v=4de_eXFRPHQ)
* The lighter color means the robot from a younger generation.

## Morphology Learning of the robot
In this case, we have 4 types of cubes with different material properties. And genetic algorithm will use these four types of cubes to construct a robot automatically. The goal is same with above to make it move faster.
Here is the result, and **click** below image you can see the result video.
