# Extended-Kalman-Filter
Udacity CarND Term 2, Project 1 - Extended Kalman Filters

## Project Basics
In this project, I used C++ to write a program taking in radar and lidar data to track position using Extended Kalman Filters.

The code will make a prediction based on the sensor measurement and updating the expected position.

## Build instructions
Assuming you have 'cmake' and 'make' already:
1. Clone this repo.
2. Make a build directory: mkdir build && cd build
3. Compile: cmake .. && make
4. Run it: ./ExtendedKF path/to/input.txt path/to/output.txt. You can find some sample inputs in 'data/'.
    eg. ./ExtendedKF ../data/sample-laser-radar-measurement-data-1.txt output.txt

## Results
In two different simulated runs, my Extended Kalman Filter produces the below results. The x-position is shown as 'px', y-position as 'py', velocity in the x-direction is 'vx', while velocity in the y-direction is 'vy'. Residual error is calculated by mean squared error (MSE).

*Test One*

| Input |   MSE   |
| ----- | ------- |
|  px   | Content |
|  py   | Content |
|  vx   | Content |
|  vy   | Content |

![Test One Visualization](https://github.com/mvirgo/Extended-Kalman-Filter/blob/master/vis_1.png "Test One Visualization")

*Test Two*

| Input |   MSE   |
| ----- | ------- |
|  px   | Content |
|  py   | Content |
|  vx   | Content |
|  vy   | Content |

![Test Two Visualization](https://github.com/mvirgo/Extended-Kalman-Filter/blob/master/vis_2.png "Test Two Visualization")
