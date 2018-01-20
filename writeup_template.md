﻿
[//]: # (Image References)
[image1]: .CarND-Extended-Kalman-Filter-Project/results/Dataset_1.png
[image2]: .CarND-Extended-Kalman-Filter-Project/results/Dataset_2.png



# Extended Kalman Filter
This is Project 1 of Udacity Self-Driving Car Nanodegree program. 
The goal of the project is to apply Extended Kalman Filter to fuse data from LIDAR and Radar sensors using C++.

The project was created with the Udacity [Starter Code](https://github.com/udacity/CarND-Extended-Kalman-Filter-Project).

## Content of this repo
- `scr` a directory with the project code:
  - `main.cpp` - reads in data, calls a function to run the Kalman filter, calls a function to calculate RMSE
  - `FusionEKF.cpp` - initializes the filter, calls the predict function, calls the update function
  - `kalman_filter.cpp`- defines the predict function, the update function for lidar, and the update function for radar
  - `tools.cpp` - a function to calculate RMSE and the Jacobian matrix
- `data`  a directory with two input files, provided by Udacity
- `results`  a directory with output and log files
- `Docs` a directory with files formats description
- `ide_profiles`
- `CMakeLists.txt`
- `README.md` Description of the Project by Udacity
- `writeup_template.md` for submission of this Project

##Result
The RMSE are both (Dataset_1 and Datatset_2) below the RMSE values  [x: 0.11; y: 0.11; vx: 0.52; vy: 0.52]. 


Dataset_1: `RMSE: [x: 0.0973; y: 0.0855; vx: 0.4513; vy: 0.4399]`

![alt text][image1] 


Dataset_1: `RMSE: [x: 0.0726; y: 0.0965; vx: 0.4216; vy: 0.4932`

![alt text][image2]


