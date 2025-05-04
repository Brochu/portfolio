+++
title = "Solar System Representation"
weight = 100
description = "In my first graphics programming class in University, we learned how to use the OpenGL API. This is my last project from this class."

[extra]
thumb = "imgs/projs/SolarSystem_3.png"
type = "Sherbrooke University Project"
stack = ["C++", "OpenGL"]
images = [
    "imgs/projs/SolarSystem_1.png",
    "imgs/projs/SolarSystem_2.png",
    "imgs/projs/SolarSystem_3.png",
    "imgs/projs/SolarSystem_4.png"
]
+++

This project was done while I was in a rendering course at University. With that project, we had to practice using OpenGL (using transparent textures, camera positioning and code structure) to render the solar system. It is possible to interact with the 3D rendered system by selecting a planet to focus on, zooming in and out and rotate the camera around the focused planet.

We also had to come up with a structure for our code since we had no base structure given for this project. As a team, we decided to create a tree based structure to keep our planets stored in. This way we could easily represent moons related to planets. We basically looped through the planets in the tree structure and pushed position info on a stack so moons are placed around their planet.

We also had a couple of transparent textures for the planets with rings of the solar system.

Here are some screenshots of the program when running.
