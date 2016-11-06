Read me: how all of the scripts work and how they are connected
=================================================================================================================================

This is the tidy data which got all the means and standard deviations for each measurement (including test and training)

This dataset collected from: Human Activity Recognition Using Smartphones Dataset Version 1.0
Original data source: https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip
==================================================================================================================
Step 1: download zip file from website
step 2: unzip file
step 3: read data into R
step 4: merge train and test datasets by colums, and then merge the two together (fullData)
step 5: read feature data, get colum names
step 6: find the index of mean and standard deviation, subset the mean and standard deviation to finalData
step 7: set colum name to finalData
step 8: read activity data, get the activity name, and set to finalData
step 9: set appropriate lables: t - time, f - frequence, mean - Mean, std - Std
step 10: get means by subjects and activities, and then make a new table groupData
step 11: write groupData to file


