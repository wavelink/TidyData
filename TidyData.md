# Creating a Tidy Data set


The purpose of this project is to demonstrate your ability to collect, work with, and clean a data set. The goal is to prepare tidy data that can be used for later analysis. You will be required to submit: 1) a tidy data set.  2) a link to a Github repository with your script for performing the analysis, and 3) a code book that describes the variables, the data, and any transformations or work that you performed to clean up the data called CodeBook.md. You should also include a README.md in the repo with your scripts. This repo explains how all of the scripts work and how they are connected.  

You should create one R script called run_analysis.R that does the following. 
Merges the training and the test sets to create one data set.
Extracts only the measurements on the mean and standard deviation for each measurement. 
Uses descriptive activity names to name the activities in the data set
Appropriately labels the data set with descriptive activity names. 
Creates a second, independent tidy data set with the average of each variable for each activity and each subject. 

### A full description is available at the site where the data was obtained: 
http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones 

### Here are the data for the project:
https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip 


### Create the following Data frames:

```{R}
features <- read.table("UCI HAR Dataset/features.txt")
```

```{R}
activityLabels <- read.table("UCI HAR Dataset/activity_labels.txt")
```
```{R}
xTrain <- read.table("UCI HAR Dataset/train//X_train.txt")
```
 
```{R}
yTrain <- read.table("UCI HAR Dataset/train//y_train.txt")
```
 
```{R}
subjectTrain <- read.table("UCI HAR Dataset/train//subject_train.txt")
```
```{R}
bodyAccX <- read.table("UCI HAR Dataset/train//Inertial Signals//body_acc_x_train.txt")
```
  
```{R}
bodyAccY <- read.table("UCI HAR Dataset/train//Inertial Signals//body_acc_y_train.txt")
```
   
```{R}
bodyAccZ <- read.table("UCI HAR Dataset/train//Inertial Signals//body_acc_z_train.txt")
```

```{R}
bodyGyroX <- read.table("UCI HAR Dataset/train//Inertial Signals//body_gyro_x_train.txt")
```

```{R}
bodyGyroY <- read.table("UCI HAR Dataset/train//Inertial Signals//body_gyro_y_train.txt")
```
 
```{R} 
bodyGyroZ <- read.table("UCI HAR Dataset/train//Inertial Signals//body_gyro_z_train.txt")
```

```{R}
totalAccX <- read.table("UCI HAR Dataset/train//Inertial Signals//total_acc_x_train.txt")
```

```{R}
totalAccY <- read.table("UCI HAR Dataset/train//Inertial Signals//total_acc_y_train.txt")
```

```{R}
totalAccZ <- read.table("UCI HAR Dataset/train//Inertial Signals//total_acc_z_train.txt")
```

```{R}
subjectTest <- read.table("UCI HAR Dataset/test//subject_test.txt")
```

```{R}
xTest <- read.table("UCI HAR Dataset/test//X_test.txt")
```

```{R}
yTest <- read.table("UCI HAR Dataset/test//y_test.txt")
```

```{R}
bodyAccXtest <- read.table("UCI HAR Dataset/test//Inertial Signals//body_acc_x_test.txt"
```

```{R}
bodyAccYtest <- read.table("UCI HAR Dataset/test//Inertial Signals//body_acc_y_test.txt")
```

```{R}
bodyAccZtest <- read.table("UCI HAR Dataset/test//Inertial Signals//body_acc_z_test.txt")
```

```{R]}
bodyGyroXtest <- read.table("UCI HAR Dataset/test//Inertial Signals//body_gyro_x_test.txt")
```

```{R}
bodyGyroYtest <- read.table("UCI HAR Dataset/test//Inertial Signals//body_gyro_y_test.txt")
```

```{R}
bodyGyroZtest <- read.table("UCI HAR Dataset/test//Inertial Signals//body_gyro_z_test.txt"
```

```{R}
totalAccXtest <- read.table("UCI HAR Dataset/test//Inertial Signals//total_acc_x_test.txt"
```

```{R}
totalAccYtest <- read.table("UCI HAR Dataset/test//Inertial Signals//total_acc_y_test.txt")
```

```{R}
totalAccZtest <- read.table("UCI HAR Dataset/test//Inertial Signals//total_acc_z_test.txt")
```




   
 
