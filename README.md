# Newton-Fractals
Generates Newton-Fractals(Curves that are non-differentiable at every point) using Mandelbrot algorithm.

## :computer: Setup

This version is mainly tested on Ubuntu.

### Prerequisites

1. **Install g++**

` sudo apt-get update `

` sudo apt-get install g++ `

2. **Install SFML library**

There are three ways to install SFML library:

* Using package manager

$ sudo apt-get install libsfml-dev

* Download the SDK

Download the SDK from the [download page](https://www.sfml-dev.org/download.php), unpack it and copy the files to your preferred location: either a separate path in your personal folder (like /home/me/sfml), or a standard path (like /usr/local).

* Building SFML yourself

If you want to go this way, there's a [dedicated tutorial](https://www.sfml-dev.org/tutorials/2.0/compile-with-cmake.php) on building SFML yourself.

## :wrench: Setup and run

1. Download (clone) this repository
2. In main.cpp, define the desired fractal preset you want to see
3. Type 'make' in your terminal (without quotes)
4. Type './exec.out' in your terminal (again, without quotes)
5. Enjoy the fractals

## Mandelbrot fractal:
Check out the renderer in action:

![Mandelbrot Fractal Render](https://raw.githubusercontent.com/BojanV03/SFML_Fractals/master/Images/Mandelbrot.jpg "Mandelbrot Fractal Render")
