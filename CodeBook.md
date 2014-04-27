# Code Book for Tidy data analysis

## The following Variables are used:

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

