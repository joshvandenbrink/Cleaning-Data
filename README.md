Cleaning-Data

Josh Vandenbrink
=============
Course Project for Coursera Cleaning Data course

The run_analysis.R code presented here loads the Samsung Human Activity Recognition Using Smartphones Dataset
Version 1.0


The experiments have been carried out with a group of 30 volunteers within an age bracket of 19-48 years. Each person performed six activities (WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING) wearing a smartphone (Samsung Galaxy S II) on the waist. Using its embedded accelerometer and gyroscope, we captured 3-axial linear acceleration and 3-axial angular velocity at a constant rate of 50Hz. The experiments have been video-recorded to label the data manually. The obtained dataset has been randomly partitioned into two sets, where 70% of the volunteers was selected for generating the training data and 30% the test data.

The run_analysis.R code remotely downloads the data, and unzips the file. 

The datasets are then combined into one master dataset where, column headings attacked as well as the participants of the study. 

The columns containing only data pertaining to mean or standard deviation are isolated from the whole dataset. 

Finally, the mean of each of these columns is calculated for each participant by activity combination. The resulting data is presented in a data table (tidy). 
