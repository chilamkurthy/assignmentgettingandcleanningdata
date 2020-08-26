# Tidy data set description

### The variables in the tidy data
Tidy data contains 180 rows and 68 columns. Each row has averaged variables for each subject and each activity.

### Only all the variables estimated from mean and standard deviation in the tidy set were kept.

* mean(): Mean value
* std(): Standard deviation

### The data were averaged based on subject and activity group.

Subject column is numbered sequentially from 1 to 30.
Activity column has 6 types as listed below.
1. WALKING
2. WALKING_UPSTAIRS
3. WALKING_DOWNSTAIRS
4. SITTING
5. STANDING
6. LAYING

## About the source data
The source data are from the Human Activity Recognition Using Smartphones Data Set. A full description is available at the site where the data was obtained:
http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones
Here are the data for the project: https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip 

### Variable units
Activity variable is factor type.
Subject variable is integer type.
All the other variables are numeric type.