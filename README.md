# Getting-and-Cleaning-Data-Course-Project

Steps of processes in my **run_analysis.R**

1. Match descriptive activity names to activity value in data set.
2. Merge training and test data sets to be one data set (HAR_data_all value)
3. extract only mean and sd for each measurement by using grep function with regular expression to extract column names which contain "mean" and "std" string.
4. Change labels to appropriate labels and use ***make.names*** function to make suitable name.
5. Use package dplyr to group and calculate the average of each variables for each activity and each subject.

