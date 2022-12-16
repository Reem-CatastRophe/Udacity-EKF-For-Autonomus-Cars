# Udacity EKF For Autonomus Cars
 Udacity self-driving car nanodegree Term 2 Project 1: Extended Kalman Filter in C++.
This project implements an extended Kalman filter in C++. Input data consisting of motion senseor 1 measurements (given directly as x and y positions, with some known uncertainty) and motion sensor 2 measurements (given as radius, angle, and radial velocity relative to some fixed measurement site, with some known uncertainty) are combined with a motion model to track a vehicle with much better accuracy than the individual measurements alone allow. The code presented here is designed to work with the Udacity term 2 simulation executable, and so it can't be run standalone.

Once the install for uWebSocketIO is complete, the main program can be built and ran by doing the following from the project top directory.

#Basic Build Instructions
1-Clone this repo.
2-Make a build directory: mkdir build && cd build
3-Compile: cmake .. && make
4-Run it: ./ExtendedKF


#important dependencies
cmake >= 3.5
make >= 4.1
gcc/g++ >= 5.4
