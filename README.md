# CarND-Extended-Kalman-Filter-Project
The complete project of Self-Driving Car Engineer Nanodegree Program. I done the assignment at spring, 2019. I just upload this in to github.

---

# Overview
The code of this project was completed, you can check it directly despite it need to run on simulate which provide by Udacity. In this project, the laser dataset and radar dataset was provided, we need to using this data to predict the position of the object by **EKF**.

# Evaluate
The code need to run on two datasets, and the **RMSE** between output (`px`, `py`, `vx`, `vy`), and ground true must under `[.11, .11, 0.52, 0.52]`. 

# Run Result
[result_1]: ./fig/dataset_1.jpg
[result_2]: ./fig/dataset_2.jpg
The run result of dataset 1 was show on below. 

![result of dataset 1][result_1]

The run result of dataset 2 was show on below. 

![result of dataset 2][result_2]
