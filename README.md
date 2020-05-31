# :star: Sensor Data : Understanding Correlations
## Human Activity Recognition using mobile sensor data.

Classifying different human activities on the basis of data collected from the sensors packed into our devices. <br><br>
<p align="center">
  <img width="500" height="500" src="https://github.com/rjrockzz/sensor-data-correlation/blob/master/data/ui.jpg">
</p>
<br><br>
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
* 30% of the volunteers were selected for generating the testing data.<br><br> 
**For each record it is provided:**


- Triaxial acceleration from the accelerometer (total acceleration) and the estimated body acceleration.
- Triaxial Angular velocity from the gyroscope. 
- A 561-feature vector with time and frequency domain variables. 
- Its activity label. 
- An identifier of the subject who carried out the experiment.<br><br>
**The dataset includes the following files:**


- [features_info.txt](https://github.com/rjrockzz/sensor-data-correlation-xebia/blob/master/data/features_info.txt): Shows information about the variables used on the feature vector.
- [features.txt](https://github.com/rjrockzz/sensor-data-correlation-xebia/blob/master/data/features.txt): List of all features.
- [activity_labels.txt](https://github.com/rjrockzz/sensor-data-correlation-xebia/blob/master/data/activity_labels.txt): Links the class labels with their activity name.
- 'train/X_train.txt': Training set.
- 'train/y_train.txt': Training labels.
- 'test/X_test.txt': Test set.
- 'test/y_test.txt': Test labels.<br><br>
**The following files were available for the train and test data.** 


- 'train/subject_train.txt': Each row identifies the subject who performed the activity for each window sample. Its range is from 1 to 30. 
- 'train/Inertial Signals/total_acc_x_train.txt': The acceleration signal from the smartphone accelerometer X axis in standard gravity units 'g'.The same description applies for the 'total_acc_x_train.txt' and 'total_acc_z_train.txt' files for the Y and Z axis. 
- 'train/Inertial Signals/body_acc_x_train.txt': The body acceleration signal obtained by subtracting the gravity from the total acceleration. 
- 'train/Inertial Signals/body_gyro_x_train.txt': The angular velocity vector measured by the gyroscope for each window sample. The units are radians/second.<br><br> 
**Important notes before proceeding:**
 

- Features are normalized and bounded within [-1,1].
- Each feature vector is a row on the text file.
- The units used for the accelerations (total and body) are 'g's (gravity of earth -> 9.80665 m/seg2).
- The gyroscope units are rad/seg.
-------------------------------------------------------------------------------
<br>

**Updates report:**
<br>
1. [Update 1](https://github.com/rjrockzz/sensor-data-correlation/blob/master/Daily%20Update/har1.ipynb) : Dataset import and formatting.<br>
2. [Update 2](https://github.com/rjrockzz/sensor-data-correlation/blob/master/Daily%20Update/har2.ipynb) : Added Visualizations and Plots, Data cleaning.
3. [Update 3](https://github.com/rjrockzz/sensor-data-correlation/blob/master/Daily%20Update/har3.ipynb) : Dimensionality Reduction using [Uniform Manifold Approximation and Projection (UMAP).](https://github.com/lmcinnes/umap)
4. [Update 4](https://github.com/rjrockzz/sensor-data-correlation/blob/master/Daily%20Update/har4.ipynb) : Applied ML models for a comparative study.
5. [Update 5](https://github.com/rjrockzz/sensor-data-correlation/blob/master/Daily%20Update/har5.ipynb) : Model Comparison and Data Preparation for Applying LSTMs.
6. [Update 6](https://github.com/rjrockzz/sensor-data-correlation/blob/master/Daily%20Update/har6.ipynb) : Tuning HyperParameters using [Hyperas](https://github.com/maxpumperla/hyperas/commits?author=maxpumperla) and using the best parameters for LSTMs.
7. [Update 7 : Final](https://github.com/rjrockzz/sensor-data-correlation/blob/master/Daily%20Update/har7.ipynb) : Deployed the model using Pickle and Created a small Flask app for the project.
