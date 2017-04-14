# Extended-Kalman-Filter
Udacity CarND Term 2, Project 1 - Extended Kalman Filters

## Project Basics
In this project, I used C++ to write a program taking in radar and lidar data to track position using Extended Kalman Filters.

The code will make a prediction based on the sensor measurement and then update the expected position. See files in the 'src' folder for the primary C++ files making up this project.

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
|  px   | 0.06516 |
|  py   | 0.06054 |
|  vx   | 0.53321 |
|  vy   | 0.54419 |

![Test One Visualization](https://github.com/mvirgo/Extended-Kalman-Filter/blob/master/vis_1.png "Test One Visualization")

*Test Two*

| Input |   MSE   |
| ----- | ------- |
|  px   | 0.18569 |
|  py   | 0.19021 |
|  vx   | 0.47401 |
|  vy   | 0.82501 |

![Test Two Visualization](https://github.com/mvirgo/Extended-Kalman-Filter/blob/master/vis_2.png "Test Two Visualization")
