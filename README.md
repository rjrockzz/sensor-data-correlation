# :star: Sensor Data : Understanding Correlations.
## Human Activity Recognition using mobile sensor data.

Classifying different human activities on the basis of the data collected from the sensors packed into our devices. <br><br>
**DEPENDENCIES**
* panda
* numpy
* matplotlib
* tensorflow
* sklearn<br>

Introduction:
-------------
<br>
Smart Phones today are packed with all kinds of sensors. They generate huge amount of data and sensor data generated from these devices can certainly be put to use to derive insights. In our problem study, we intend to utilize our smartphone sensor data to recognize human activities.<br><br> 
In our project, we’ll primarily focus on classifying different human activities on the basis of the data collected from the sensors packed into our devices. To make our project scrupulous, we also plan to create a comparative study of different learning models.<br>

-----------------------------------------------------
Dataset Study:
--------

The dataset for the following problem can be downloaded from [here](https://archive.ics.uci.edu/ml/machine-learning-databases/00240/UCI%20HAR%20Dataset.zip#)
<br>
Experiments were carried out with a group of 30 volunteers.The following activites were classified.<br><br>
**Activities**
* Walking
* Walking Upstairs
* Walking Downstairs
* Sitting
* Standing
* Laying
<br>
Using embedded accelerometer and gyroscope, 3-axial linear acceleration and 3-axial angular velocity were captured at a constant rate of 50Hz.<br><br>

[**Accelerometers**](https://en.wikipedia.org/wiki/Accelerometer) detect magnitude and direction of the proper acceleration, as a vector quantity, and can be used to sense orientation (because direction of weight changes)
<br><br>
[**GyroScope**](https://en.wikipedia.org/wiki/Gyroscope) maintains orientation along a axis so that the orientation is unaffected by tilting or rotation of the mounting, according to the conservation of angular momentum.
<br><br>
The experiments have been video-recorded to label the data manually. The obtained dataset has been randomly partitioned into two sets.


* 70% of the volunteers were selected for generating the training data.<br>
* 30% of the volunteers were selected for generating the testing data. 


-------------------------------------------------------------------------------
