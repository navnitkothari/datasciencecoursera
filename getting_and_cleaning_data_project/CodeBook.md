Getting and Cleaning Data - Project


Description

This codebook was created by Navneet Kothari on 11th of August, 2016. It was created as part of course assignment of Getting and Cleaning Data at Coursera. This document contains additional information about the variables, data and transformations used in the course project.


Source Data

A full description of the data used in this project can be found at The UCI Machine Learning Repository


Data Set Information

The experiments have been carried out with a group of 30 volunteers within an age bracket of 19-48 years. Each person performed six activities (WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING) wearing a smartphone (Samsung Galaxy S II) on the waist. Using its embedded accelerometer and gyroscope, we captured 3-axial linear acceleration and 3-axial angular velocity at a constant rate of 50Hz. The experiments have been video-recorded to label the data manually. The obtained dataset has been randomly partitioned into two sets, where 70% of the volunteers was selected for generating the training data and 30% the test data.

The sensor signals (accelerometer and gyroscope) were pre-processed by applying noise filters and then sampled in fixed-width sliding windows of 2.56 sec and 50% overlap (128 readings/window). The sensor acceleration signal, which has gravitational and body motion components, was separated using a Butterworth low-pass filter into body acceleration and gravity. The gravitational force is assumed to have only low frequency components, therefore a filter with 0.3 Hz cutoff frequency was used. From each window, a vector of features was obtained by calculating variables from the time and frequency domain.


Identifiers

    subject - The ID of the test subject
    activity - The type of activity performed when the corresponding measurements were taken


Variable List

    tBodyAccMeanX
    tBodyAccMeanY
    tBodyAccMeanZ
    tBodyAccStdX
    tBodyAccStdY
    tBodyAccStdZ
    tGravityAccMeanX
    tGravityAccMeanY
    tGravityAccMeanZ
    tGravityAccStdX
    tGravityAccStdY
    tGravityAccStdZ
    tBodyAccJerkMeanX
    tBodyAccJerkMeanY
    tBodyAccJerkMeanZ
    tBodyAccJerkStdX
    tBodyAccJerkStdY
    tBodyAccJerkStdZ
    tBodyGyroMeanX
    tBodyGyroMeanY
    tBodyGyroMeanZ
    tBodyGyroStdX
    tBodyGyroStdY
    tBodyGyroStdZ
    tBodyGyroJerkMeanX
    tBodyGyroJerkMeanY
    tBodyGyroJerkMeanZ
    tBodyGyroJerkStdX
    tBodyGyroJerkStdY
    tBodyGyroJerkStdZ
    tBodyAccMagMean
    tBodyAccMagStd
    tGravityAccMagMean
    tGravityAccMagStd
    tBodyAccJerkMagMean
    tBodyAccJerkMagStd
    tBodyGyroMagMean
    tBodyGyroMagStd
    tBodyGyroJerkMagMean
    tBodyGyroJerkMagStd
    fBodyAccMeanX
    fBodyAccMeanY
    fBodyAccMeanZ
    fBodyAccStdX
    fBodyAccStdY
    fBodyAccStdZ
    fBodyAccMeanFreqX
    fBodyAccMeanFreqY
    fBodyAccMeanFreqZ
    fBodyAccJerkMeanX
    fBodyAccJerkMeanY
    fBodyAccJerkMeanZ
    fBodyAccJerkStdX
    fBodyAccJerkStdY
    fBodyAccJerkStdZ
    fBodyAccJerkMeanFreqX
    fBodyAccJerkMeanFreqY
    fBodyAccJerkMeanFreqZ
    fBodyGyroMeanX
    fBodyGyroMeanY
    fBodyGyroMeanZ
    fBodyGyroStdX
    fBodyGyroStdY
    fBodyGyroStdZ
    fBodyGyroMeanFreqX
    fBodyGyroMeanFreqY
    fBodyGyroMeanFreqZ
    fBodyAccMagMean
    fBodyAccMagStd
    fBodyAccMagMeanFreq
    fBodyBodyAccJerkMagMean
    fBodyBodyAccJerkMagStd
    fBodyBodyAccJerkMagMeanFreq
    fBodyBodyGyroMagMean
    fBodyBodyGyroMagStd
    fBodyBodyGyroMagMeanFreq
    fBodyBodyGyroJerkMagMean
    fBodyBodyGyroJerkMagStd
    fBodyBodyGyroJerkMagMeanFreq

Activity Labels

    WALKING             : Subject was Walking
    WALKING_UPSTAIRS    : Subject was Walking Up a Staircase
    WALKING_DOWNSTAIRS  : Subject was Walking Down a Staircase
    SITTING             : Subject was Sitting
    STANDING            : Subject was Standing
    LAYING              : Subject was Laying Down


Data Transformation

The raw data sets are processed with run_analysis.R script.

The train and test datasets are merged. Variables with mean and standard deviation are extracted. As a result, the tidy set is created.
