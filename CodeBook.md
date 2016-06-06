Getting and Cleaning Data Course Project CodeBook
-------------------------------------------------
This codebook describes the variables, the data, and any transformations or work that i performed to clean up the data for the
"Getting and Cleaning Data Course Project"
Original data source:
https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip
The data linked to from the course website represent data collected from the accelerometers from the Samsung Galaxy S smartphone.
A full description is available at the site where the data was obtained:
http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

Worked Performed in run_analysis.R
----------------------------------
1)Download the data from original data source
2)Unzip
3)Read activity labels and features
4)Extract the data on mean and standard deviation
5)Read the train and test datasets
6)Merge the datasets and add labels
7)Convert activities and subjects into factors
8)Write the tidy dataset file
