# RU83C: Rubik's Cube Solving Robot

BASE VERSION: [here](https://github.com/Mummanajagadeesh/V-RU81K5CU83)


## Overview

RU83C is a Rubik's Cube-solving robot that leverages computer vision (CV), mechanical design, and electronics to solve a scrambled Rubik's Cube using the Kociemba algorithm. The robot features a camera that captures the current state of the scrambled cube, processes the image using CV, and calculates the solution. A mechanical holder grips the cube securely, and the robot executes the necessary moves to solve it.

## Features

**Computer Vision**: A camera-based system to detect the current state of the Rubik's Cube, using image processing techniques to translate the visual input into a digital cube representation.

**Mechanical Design**: A custom-built holder with an efficient gripping system to securely hold and rotate the cube while executing the solution.

**Kociemba Algorithm**: The Kociemba algorithm is employed to calculate the optimal solution for the scrambled state.

**Electronics**: The system uses electronics to control the motors and mechanical components, translating the calculated moves into physical actions.


## Structure

The project is divided into several key parts:

1. CV (Computer Vision): Responsible for recognizing the scrambled state of the cube via a camera.


2. Mechanical Design: Focused on the creation of the holder and gripping mechanisms to manipulate the cube.


3. Algorithm: Implementation of the Kociemba algorithm to calculate the solution to any scrambled state.


4. Electronics: Controls and coordinates the robot’s movements based on the computed solution.



## Base Version

A base version of this project was previously developed in simulation, where users could manually or automatically scramble a virtual cube in Unity. The solution for the scrambled cube was calculated and displayed in the virtual environment. This was an intermediate step, and the current version represents the full hardware implementation of the Rubik's Cube-solving robot.

## Getting Started

Instructions on how to set up and run the project will be added soon.

## License

This project is licensed under the MIT License.