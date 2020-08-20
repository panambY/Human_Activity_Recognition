# Human_Activity_Recognition
Predict the activity category of a human.

## Abstract

Activity recognition data set built from the recordings of 30 subjects performing basic activities and postural transitions while carrying a waist-mounted smartphone with embedded inertial sensors.  

- **Data Set Characteristics:** Multivariate, Time-Series <br>
- **Attribute Characteristics:** Real <br>
- **Associated Tasks:** Classification <br>
- **Number of Instances:** 10919 <br>
- **Number of Attributes:** 561 <br>
- **Missing Values:** N/A <br>
- **Area:** Life <br>
- **Date Donated:** 2015-07-29

This is a UCI Machine Learning Repository project which can be found in this link: <a href="http://archive.ics.uci.edu/ml/datasets/Smartphone-Based+Recognition+of+Human+Activities+and+Postural+Transitions"> Smartphone-Based Recognition of Human Activities and Postural Transitions </a>

<p align="center">
  <img src="https://github.com/panambY/Human_Activity_Recognition/blob/master/image/human_activity_recognition.jpg">
</p>

## Source:

Jorge L. Reyes-Ortiz(1,2), Davide Anguita(1), Luca Oneto(1) and Xavier Parra(2)
1 - Smartlab, DIBRIS - UniversitÃ  degli Studi di Genova, Genoa (16145), Italy.
2 - CETpD - Universitat PolitÃ¨cnica de Catalunya. Vilanova i la GeltrÃº (08800), Spain
har '@' smartlab.ws
www.smartlab.ws

## Data Set Information:

The experiments were carried out with a group of 30 volunteers within an age bracket of 19-48 years. They performed a protocol of activities composed of six basic activities: three static postures (standing, sitting, lying) and three dynamic activities (walking, walking downstairs and walking upstairs). The experiment also included postural transitions that occurred between the static postures. These are: stand-to-sit, sit-to-stand, sit-to-lie, lie-to-sit, stand-to-lie, and lie-to-stand. All the participants were wearing a smartphone (Samsung Galaxy S II) on the waist during the experiment execution. We captured 3-axial linear acceleration and 3-axial angular velocity at a constant rate of 50Hz using the embedded accelerometer and gyroscope of the device. The experiments were video-recorded to label the data manually. The obtained dataset was randomly partitioned into two sets, where 70% of the volunteers was selected for generating the training data and 30% the test data.

The sensor signals (accelerometer and gyroscope) were pre-processed by applying noise filters and then sampled in fixed-width sliding windows of 2.56 sec and 50% overlap (128 readings/window). The sensor acceleration signal, which has gravitational and body motion components, was separated using a Butterworth low-pass filter into body acceleration and gravity. The gravitational force is assumed to have only low frequency components, therefore a filter with 0.3 Hz cutoff frequency was used. From each window, a vector of 561 features was obtained by calculating variables from the time and frequency domain. See 'features_info.txt' for more details.

This dataset is an updated version of the UCI Human Activity Recognition Using smartphones Dataset that can be found at: <a href= "https://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones"> [Web Link] </a>
This version provides the original raw inertial signals from the smartphone sensors, instead of the ones pre-processed into windows which were provided in version 1. This change was done in order to be able to make online tests with the raw data. Moreover, the activity labels were updated in order to include postural transitions that were not part of the previous version of the dataset.

## Attribute Information:

The dataset is then divided in two parts and they can be used separately.

1. Inertial sensor data
- Raw triaxial signals from the accelerometer and gyroscope of all the trials with with participants. <br>
- The labels of all the performed activities.

2. Records of activity windows. Each one composed of:
- A 561-feature vector with time and frequency domain variables. <br>
- Its associated activity label. <br>
- An identifier of the subject who carried out the experiment.

### The dataset includes the following files:

- 'README.txt' <br>
- The raw triaxial acceleration signal for the experiment number XX and associated to the user number YY. Every row is one acceleration sample (three axis) captured at a frequency of 50Hz. <br>
- The raw triaxial angular speed signal for the experiment number XX and associated to the user number YY. Every row is one angular velocity sample (three axis) captured at a frequency of 50Hz. <br>
- Include all the activity labels available for the dataset (1 per row).
Column 1: experiment number ID, <br>
Column 2: user number ID, <br>
Column 3: activity number ID <br>
Column 4: Label start point (in number of signal log samples (recorded at 50Hz)) <br>
Column 5: Label end point (in number of signal log samples)
- 'features_info.txt': Shows information about the variables used on the feature vector. <br>
- 'features.txt': List of all features. <br>
- 'activity_labels.txt': Links the activity ID with their activity name. <br>
- Training set. <br>
- Training labels. <br>
- Test set. <br>
- Test labels. <br>
- Each row identifies the subject who performed the activity for each window sample. Its range is from 1 to 30. <br>
- Each row identifies the subject who performed the activity for each window sample. Its range is from 1 to 30.

### Notes:

- Features are normalized and bounded within [-1,1]. <br>
- Each feature vector is a row on the 'X' and 'y' files. <br>
- The units used for the accelerations (total and body) are 'g's (gravity of earth -> 9.80665 m/seg2). <br>
- The gyroscope units are rad/seg. <br>
- A video of the experiment including an example of the 6 recorded activities with one of the participants can be seen in the following link: <a href="http://www.youtube.com/watch?v=XOEN9W05_4A">[Web Link]</a>

For more information about this dataset please contact har '@' smartlab.ws or check our website www.smartlab.ws
