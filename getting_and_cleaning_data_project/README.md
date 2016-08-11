Getting and Cleaning Data - Project

This repository hosts the R code and documentation files for the Data Science course Getting and Cleaning Data available at Coursera.

The R script, run_analysis.R, does the following:

    Download the dataset if it does not already exist in the working directory
    Loads the feature and activity infomation
    Loads the training and test datasets, keeping only those columns which reflects a mean or standard deviation
    Loads the activity and subject data for each dataset and merges those columns with the dataset
    Merges the two datasets to create one dataset
    Converts the activity and subject columns into factors
    Creates a tidy dataset that consists of the average value of each variable for each activity and each subject.

The end result is shown in the file Tidy_Data.txt.

CodeBook.md describes the variables, the data, and any transformations or work that was performed to clean up the data.
