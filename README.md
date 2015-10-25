# Getting and Cleaning Data - Course Project

The R script called run_analysis.R that does the following.

* Merges the training and the test sets to create one data set.
* Extracts only the measurements on the mean and standard deviation for each measurement.
* Uses descriptive activity names to name the activities in the data set
* Appropriately labels the data set with descriptive activity names.
* Creates a second, independent tidy data set with the average of each variable for each activity and each subject.

The following steps are required to run this code:

* Download the data source and put into a folder on your local drive. You'll have a UCI HAR Dataset folder.
* Set your working directory to the folder in which the UCI HAR Dataset folder has been placed using the setwd() command.
* Run run_analysis.R to generate the new tidy data file tidy_data.txt in your working directory.
