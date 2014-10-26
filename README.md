Getting_and_Cleaning_Data
=======================
## This is a Course project for the Cousera Getting and Cleaning Data Class website: https://www.coursera.org/course/getdata) 
The purpose of this project is to demonstrate your ability to collect, work with, and clean a data set. The goal is to   prepare tidy data that can be used for later analysis. You will be graded by your peers on a series of yes/no questions related to the project. You will be required to submit: 1) a tidy data set as described below, 2) a link to a Github repository with your script for performing the analysis, and 3) a code book that describes the variables, the data, and any transformations or work that you performed to clean up the data called CodeBook.md. You should also include a README.md in the repo with your scripts. This repo explains how all of the scripts work and how they are connected.  
One of the most exciting areas in all of data science right now is wearable computing - see for example this article . Companies like Fitbit, Nike, and Jawbone Up are racing to develop the most advanced algorithms to attract new users. The data linked to from the course website represent data collected from the accelerometers from the Samsung Galaxy S smartphone. A full description is available at the site where the data was obtained: 
http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones 
Here are the data for the project: 
data source: https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip 
 You should create one R script called run_analysis.R that does the following. 
1.	Merges the training and the test sets to create one data set.
2.	Extracts only the measurements on the mean and standard deviation for each measurement. 
3.	Uses descriptive activity names to name the activities in the data set
4.	Appropriately labels the data set with descriptive variable names. 
5.	From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.
6. Please upload the tidy data set created in step 5 of the instructions. Please upload your data set as a txt file created with write.table() using row.name=FALSE (do not cut and paste a dataset directly into the text box, as this may cause errors saving your submission).
## Steps to work on this course project

1. Download and unzip the data source and put into a folder on your drive. When unzipped, a `UCI HAR Dataset` folder is created.
2. Put `run_analysis.R` in the `UCI HAR Dataset` folder, then set the `UCI HAR Dataset` folder as your working directory using `setwd()` function or move the `UCI HAR Dataset` folder to your current working directory.
3. Run `source code ("run_analysis.R")` from your working directory.
4.  "run_analysis.R" will generate a new file `tiny_data.txt` in your working directory.
## Dependencies
The Source Code `run_analysis.R’ will automatically install the dependencies, but will ask you for the closet repository for the download. It depends on ‘reshape’, curl and `data.table`. 
=======================
