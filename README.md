# Read me: how all of the scripts work and how they are connected
=================================================================================================================================
This is the tidy data which got all the means and standard deviations for each measurement (including test and training)<br /> 
This dataset collected from: Human Activity Recognition Using Smartphones Dataset Version 1.0<br /> 
Original data source: https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip<br /> 

Step 1: download zip file from website<br /> 
step 2: unzip file<br /> 
step 3: read data into R<br /> 
step 4: merge train and test datasets by colums, and then merge the two together (fullData)<br /> 
step 5: read feature data, get colum names<br /> 
step 6: find the index of mean and standard deviation, subset the mean and standard deviation to finalData<br /> 
step 7: set colum name to finalData<br /> 
step 8: read activity data, get the activity name, and set to finalData<br /> 
step 9: set appropriate lables: t - time, f - frequence, mean - Mean, std - Std<br /> 
step 10: get means by subjects and activities, and then make a new table groupData<br /> 
step 11: write groupData to file<br /> 


