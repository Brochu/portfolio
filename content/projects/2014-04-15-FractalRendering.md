+++
title = "Parallel Fractal Rendering"
weight = 95
description = "University project in the scope of the parallel programming class. Here we render fractal formulas with a parallel algorithm."

[extra]
thumb = "imgs/projs/FractalProject_1.png"
type = "Sherbrooke University Project"
stack = ["C#"]
images = [
    "imgs/projs/FractalProject_1.png",
    "imgs/projs/FractalProject_2.png",
    "imgs/projs/FractalProject_3.png",
    "imgs/projs/FractalProject_4.png",
    "imgs/projs/FractalProject_5.png",
    "imgs/projs/FractalProject_6.png"
]
+++

When I was in a parallelism course at Sherbrooke University, we had to choose a project to complete in a team for the end of the course. The project idea had to make us practice the parallel processing aspect of computer programming. We had to find an idea that we could split the process so it could be done faster. We figured that since a pixel in an image usually do not affect the other pixels in the image, we could generate and render an image faster if the different pixels on separate threads.

We chose to generate the Mandelbrot set fractal and render this image to the screen. We also wanted to let the user zoom-in on specific parts of the image to see it in greater details. One interesting thing we encountered while implementing the zoom functionality. We saw that when zooming a lot in an image, we started seeing less and less details. This actually happened since the double data type we used was not precise enough to represent all the details of the image.

We actually tested with different number of threads to see the optimal time we could get. At the same time, we saw that splitting the process into threads was always faster.

Here are some screenshots of the results rendered by our program.
