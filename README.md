# Getting Clean Data Assignment
This repo was created to finish the assignment for week 4 of Getting and Cleaning Data Coursera course.

1. Download and unzip the data file into your R working directory.
2. Download the R source code into your R working directory.
3. Execute R source code to generate tidy data file.

## Files:

* CodeBook.md describes the how to use all this, variables, the data, and any transformations or work that was performed to clean up the data.

* run_analysis.R contains all the code to perform the analyses described in the 5 steps. They can be launched in RStudio by just importing the file. Here are the five steps:

1. Merges the training and the test sets to create one data set, using command rbind to combine.

2. Extracts only the measurements on the mean and standard deviation for each measurement. Using grep command to get column indexes.

3. Uses descriptive activity names to name the activities in the data set. Converting activity labels to character.

4. Appropriately labels the data set with descriptive variable names. Giving descriptive names to variable column.

5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject. Uses pipeline command to create a new tidy dataset with command group_by and summarize_each in dplyr package

* tidyData.txt is the output of the final step