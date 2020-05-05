# :star: Sensor Data : Understanding Correlations.
## Human Activity Recognition using mobile sensor data.

Classifying different human activities on the basis of the data collected from the sensors packed into our devices. <br><br>
**DEPENDENCIES**
* panda
* numpy
* matplotlib
* tensorflow
* sklearn
<br>

Introduction:
-------------
<br>
Smart Phones today are packed with all kinds of sensors. They generate huge amount of data and sensor data generated from these devices can certainly be put to use to derive insights. In our problem study, we intend to utilize our smartphone sensor data to recognize human activities.<br><br> 
In our project, we’ll primarily focus on classifying different human activities on the basis of the data collected from the sensors packed into our devices. To make our project scrupulous, we also plan to create a comparative study of different learning models.

-----------------------------------------------------
Dataset Study:
--------

The dataset for the following problem can be downloaded from [here](https://archive.ics.uci.edu/ml/machine-learning-databases/00240/UCI%20HAR%20Dataset.zip#)
<br>
The experiments have been carried out with a group of 30 volunteers.<br><br>
**Activities**
* Walking
* Walking Upstairs
* Walking Downstairs
* Sitting
* Standing
* Laying
<br>
Using embedded accelerometer and gyroscope, 3-axial linear acceleration and 3-axial angular velocity were captured at a constant rate of 50Hz. The experiments have been video-recorded to label the data manually. The obtained dataset has been randomly partitioned into two sets.<br>
* 70% of the volunteers were selected for generating the training data.<br>
* 30% of the volunteers were selected for generating the testing data. 
<br>
The sensor signals (accelerometer and gyroscope) were pre-processed by applying noise filters and then sampled in fixed-width sliding windows of 2.56 sec and 50% overlap (128 readings/window). The sensor acceleration signal, which has gravitational and body motion components, was separated using a Butterworth low-pass filter into body acceleration and gravity. The gravitational force is assumed to have only low frequency components, therefore a filter with 0.3 Hz cutoff frequency was used. From each window, a vector of features was obtained by calculating variables from the time and frequency domain. See 'features_info.txt' for more details. <br><br>


[**Accelerometers**](https://en.wikipedia.org/wiki/Accelerometer) detect magnitude and direction of the proper acceleration, as a vector quantity, and can be used to sense orientation (because direction of weight changes)
<br><br>
[**GyroScope**](https://en.wikipedia.org/wiki/Gyroscope) maintains orientation along a axis so that the orientation is unaffected by tilting or rotation of the mounting, according to the conservation of angular momentum.
<br><br>

-------------------------------------------------------------------------------
