## csca-5632-unsupervised-algorithms-in-machine-learning-final-project
## Problem Statement

The proliferation of wearable devices and smartphones equipped with sensors like accelerometers and gyroscopes has enabled continuous monitoring of human physical activities.
Recognizing and classifying these activities can have significant applications in healthcare, sports, and human-computer interaction.

This project aims to perform unsupervised clustering on the Human Activity Recognition (HAR) dataset using data collected from smartphones. By clustering the sensor data, we aim to identify patterns in human movements and potentially recognize different activities without relying on labeled data.
## Dataset Description

The UCI HAR Dataset contains recordings of 30 subjects performing activities of daily living (WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING) while carrying a waist-mounted smartphone with embedded inertial sensors. The dataset includes:

* Triaxial acceleration from the accelerometer (total acceleration) and the estimated body acceleration.
* Triaxial Angular velocity from the gyroscope.
* A 561-feature vector with time and frequency domain variables.
* Its activity label. 
* An identifier of the subject who carried out the experiment.

The dataset includes the following files:
=========================================

- 'README.txt'

- 'features_info.txt': Shows information about the variables used on the feature vector.

- 'features.txt': List of all features.

- 'activity_labels.txt': Links the class labels with their activity name.

- 'train/X_train.txt': Training set.

- 'train/y_train.txt': Training labels.

- 'test/X_test.txt': Test set.

- 'test/y_test.txt': Test labels.

The following files are available for the train and test data. 

- 'train/subject_train.txt': Each row identifies the subject who performed the activity for each window sample. Its range is from 1 to 30. 

- 'train/Inertial Signals/total_acc_x_train.txt': The acceleration signal from the smartphone accelerometer X axis in standard gravity units 'g'. Every row shows a 128 element vector. The same description applies for the 'total_acc_x_train.txt' and 'total_acc_z_train.txt' files for the Y and Z axis. 

- 'train/Inertial Signals/body_acc_x_train.txt': The body acceleration signal obtained by subtracting the gravity from the total acceleration. 

- 'train/Inertial Signals/body_gyro_x_train.txt': The angular velocity vector measured by the gyroscope for each window sample. The units are radians/second. 

Notes: 
======
- Features are normalized and bounded within [-1,1].
- Each feature vector is a row on the text file.
- The units used for the accelerations (total and body) are 'g's (gravity of earth -> 9.80665 m/seg2).
- The gyroscope units are rad/seg.
- A video of the experiment including an example of the 6 recorded activities with one of the participants can be seen in the following link: http://www.youtube.com/watch?v=XOEN9W05_4A

Dataset Source: https://archive.ics.uci.edu/dataset/240/human+activity+recognition+using+smartphones

## Getting Started

### Prerequisites

- Python 3.x
- Jupyter Notebook
- Libraries:
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - scikit-learn

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/himanshudongre/human-activity-recognition.git
2. Navigate to the project directory:
   ```bash
   cd human-activity-recognition
3. Install the required packages
4. Open the Jupyter Notebook:
   ```bash
   jupyter notebook notebooks/human-activity-recognition-using-smartphones.ipynb
5. Run the cells in the notebook to execute the data analysis and model building steps.
