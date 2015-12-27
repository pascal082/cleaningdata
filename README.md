## Getting and Cleaning Data


You should create one R script called run_analysis.R that does the following.

Merges the training and the test sets to create one data set.
Extracts only the measurements on the mean and standard deviation for each measurement.
Uses descriptive activity names to name the activities in the data set
Appropriately labels the data set with descriptive activity names.
Creates a second, independent tidy data set with the average of each variable for each activity and each subject.
Steps to work on this course project

Download the data source and put into a folder on your local drive. You'll have a cleaningData folder.
Put run_analysis.R in the parent folder of cleaningData folder, 
Run run_analysis.R, which will generate a new file tinydata.txt in your working directory.

Dependencies

reshape2 and data.table,which will be install automatically
