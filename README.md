# CPPND: Capstone Snake Game Example

This is a starter repo for the Capstone project in the [Udacity C++ Nanodegree Program](https://www.udacity.com/course/c-plus-plus-nanodegree--nd213). The code for this repo was inspired by [this](https://codereview.stackexchange.com/questions/212296/snake-game-in-c-with-sdl) excellent StackOverflow post and set of responses.

<img src="snake_game.gif"/>

Few new features have been added to the original game.  
1. Game can be pause and resume anytime with space-bar key (User score can be seen on terminal.
2. Color of Snake and color of food changes based on user's score.
3. Speed of snake changes after every 5 points.

## Dependencies for Running Locally
* cmake >= 3.7
  * All OSes: [click here for installation instructions](https://cmake.org/install/)
* make >= 4.1 (Linux, Mac), 3.81 (Windows)
  * Linux: make is installed by default on most Linux distros
  * Mac: [install Xcode command line tools to get make](https://developer.apple.com/xcode/features/)
  * Windows: [Click here for installation instructions](http://gnuwin32.sourceforge.net/packages/make.htm)
* SDL2 >= 2.0
  * All installation instructions can be found [here](https://wiki.libsdl.org/Installation)
  >Note that for Linux, an `apt` or `apt-get` installation is preferred to building from source. 
* gcc/g++ >= 5.4
  * Linux: gcc / g++ is installed by default on most Linux distros
  * Mac: same deal as make - [install Xcode command line tools](https://developer.apple.com/xcode/features/)
  * Windows: recommend using [MinGW](http://www.mingw.org/)

## Basic Build Instructions

1. Clone this repo.
2. Make a build directory in the top level directory: `mkdir build && cd build`
3. Compile: `cmake .. && make`
4. Run it: `./SnakeGame`.


## CC Attribution-ShareAlike 4.0 International


Shield: [![CC BY-SA 4.0][cc-by-sa-shield]][cc-by-sa]

This work is licensed under a
[Creative Commons Attribution-ShareAlike 4.0 International License][cc-by-sa].

[![CC BY-SA 4.0][cc-by-sa-image]][cc-by-sa]

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/
[cc-by-sa-image]: https://licensebuttons.net/l/by-sa/4.0/88x31.png
[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg

## Project Specification

### README (All Rubric Points REQUIRED)

| _Done_  | _Criteria_                                                           | _Meets Specifications_                                                                                                                                                                                                                                                                      |
| :-----: | :------------------------------------------------------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| &#9745; | A `README` with instructions is included with the project            | The README is included with the project and has instructions for building/running the project. <br><br>If any additional libraries are needed to run the project, these are indicated with cross-platform installation instructions.<br><br>You can submit your writeup as markdown or pdf. |
| &#9745; | The `README` indicates which project is chosen.                      | The `README` describes the project you have built.<br><br>The `README` also indicates the file and class structure, along with the expected behavior or output of the program.                                                                                                              |
| &#9745; | The `README` includes information about each rubric point addressed. | The `README` indicates which rubric points are addressed. The `README` also indicates where in the code (i.e. files and line numbers) that the rubric points are addressed.                                                                                                                 |

### Compiling and Testing (All Rubric Points REQUIRED)

| _Done_  | _Criteria_                           | _Meets Specifications_                                                                                                                                                                                                      |
| :-----: | :----------------------------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| &#9745; | The submission must compile and run. | The project code must compile and run without errors. We strongly recommend using `cmake` and `make`, as provided in the starter repos. If you choose another build system, the code must compile on any reviewer platform. |

### Loops, Functions, I/O

| _Done_  | _Criteria_                                                                                     | _Meets Specifications_                                                                                                   |
| :-----: | :--------------------------------------------------------------------------------------------- | :----------------------------------------------------------------------------------------------------------------------- |
| &#9745; | The project demonstrates an understanding of C++ functions and control structures.             | A variety of control structures are used in the project.<br><br>The project code is clearly organized into functions.    |
| &#9745; | The project accepts user input and processes the input.                                        | The project accepts input from a user as part of the necessary operation of the program.                                 |

### Object Oriented Programming

| _Done_  | _Criteria_                                                           | _Meets Specifications_                                                                                                                                                                 |
| :-----: | :------------------------------------------------------------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| &#9745; | The project uses Object Oriented Programming techniques.             | The project code is organized into classes with class attributes to hold the data, and class methods to perform tasks.                                                                 |
| &#9745; | Classes use appropriate access specifiers for class members.         | All class data members are explicitly specified as public, protected, or private                                                                                                       |
| &#9745; |	Class constructors utilize member initialization lists.				 | All class members that are set to argument values are initialized through member initialization lists.	                                                                              |																																																			  |
| &#9745; | Classes abstract implementation details from their interfaces.       | All class member functions document their effects, either through function names, comments, or formal documentation. Member functions do not change program state in undocumented ways.|
| &#9745; | Classes encapsulate behavior.                                        | Appropriate data and functions are grouped into classes. Member data that is subject to an invariant is hidden from the user. State is accessed via member functions.                  |
