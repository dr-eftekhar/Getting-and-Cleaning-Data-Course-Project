## Getting and Cleaning Data Course Project CodeBook
-------------------------------------------------
This codebook describes the variables, the data, and any transformations or work that i performed to clean up the data for the
"Getting and Cleaning Data Course Project"
Original data source:
https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip
The data linked to from the course website represent data collected from the accelerometers from the Samsung Galaxy S smartphone.
A full description is available at the site where the data was obtained:
http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

## Worked Performed in run_analysis.R
----------------------------------
1)Download the data from original data source
2)Unzip
3)Read activity labels and features
4)Extract the data on mean and standard deviation
5)Read the train and test datasets
6)Merge the datasets and add labels
7)Convert activities and subjects into factors
8)Write the tidy dataset file to local directory

## tidy_dataset.txt description
----------------------------
## Identifiers

* subject - The ID of the test subject
* activity - The type of activity performed when the corresponding measurements were taken

## Measurements

* tBodyAccMeanX
* tBodyAccMeanY
* tBodyAccMeanZ
* tBodyAccStdX
* tBodyAccStdY
* tBodyAccStdZ
* tGravityAccMeanX
* tGravityAccMeanY
* tGravityAccMeanZ
* tGravityAccStdX
* tGravityAccStdY
* tGravityAccStdZ
* tBodyAccJerkMeanX
* tBodyAccJerkMeanY
* tBodyAccJerkMeanZ
* tBodyAccJerkStdX
* tBodyAccJerkStdY
* tBodyAccJerkStdZ
* tBodyGyroMeanX
* tBodyGyroMeanY
* tBodyGyroMeanZ
* tBodyGyroStdX
* tBodyGyroStdY
* tBodyGyroStdZ
* tBodyGyroJerkMeanX
* tBodyGyroJerkMeanY
* tBodyGyroJerkMeanZ
* tBodyGyroJerkStdX
* tBodyGyroJerkStdY
* tBodyGyroJerkStdZ
* tBodyAccMagMean
* tBodyAccMagStd
* tGravityAccMagMean
* tGravityAccMagStd
* tBodyAccJerkMagMean
* tBodyAccJerkMagStd
* tBodyGyroMagMean
* tBodyGyroMagStd
* tBodyGyroJerkMagMean
* tBodyGyroJerkMagStd
* fBodyAccMeanX
* fBodyAccMeanY
* fBodyAccMeanZ
* fBodyAccStdX
* fBodyAccStdY
* fBodyAccStdZ
* fBodyAccMeanFreqX
* fBodyAccMeanFreqY
* fBodyAccMeanFreqZ
* fBodyAccJerkMeanX
* fBodyAccJerkMeanY
* fBodyAccJerkMeanZ
* fBodyAccJerkStdX
* fBodyAccJerkStdY
* fBodyAccJerkStdZ
* fBodyAccJerkMeanFreqX
* fBodyAccJerkMeanFreqY
* fBodyAccJerkMeanFreqZ
* fBodyGyroMeanX
* fBodyGyroMeanY
* fBodyGyroMeanZ
* fBodyGyroStdX
* fBodyGyroStdY
* fBodyGyroStdZ
* fBodyGyroMeanFreqX
* fBodyGyroMeanFreqY
* fBodyGyroMeanFreqZ
* fBodyAccMagMean
* fBodyAccMagStd
* fBodyAccMagMeanFreq
* fBodyBodyAccJerkMagMean
* fBodyBodyAccJerkMagStd
* fBodyBodyAccJerkMagMeanFreq
* fBodyBodyGyroMagMean
* fBodyBodyGyroMagStd
* fBodyBodyGyroMagMeanFreq
* fBodyBodyGyroJerkMagMean
* fBodyBodyGyroJerkMagStd
* fBodyBodyGyroJerkMagMeanFreq

## Activity Labels

* WALKING (value 1): subject was walking during the test
* WALKING_UPSTAIRS (value 2): subject was walking up a staircase during the test
* WALKING_DOWNSTAIRS (value 3): subject was walking down a staircase during the test
* SITTING (value 4): subject was sitting during the test
* STANDING (value 5): subject was standing during the test
* LAYING (value 6): subject was laying down during the test
