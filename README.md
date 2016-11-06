
# This is the course project for Getting and Cleaning Data course on Coursera. Source file is run_analysis.R, which does the following things: <h1>


**Download the dataset if it does not already exist in the working directory.**
######-Check if zip has already been downloaded <H6>
######-Check if zip has already been unzipped <H6>

**Load activity, subject and feature info. Read data from the files into the variables.**
######-Read the Activity files. <H6>
######-Read the Subject files. <H6>
######-Read Features files. <H6>

**Merges the training and the test sets to create one data set.**
######-Concatenate the data tables by rows. <H6>
######-set names to variables. <H6>
######-Merge columns to get the data frame Data for all data. <H6>

**Extracts only the measurements on the mean and standard deviation for each measurement.**
######-Subset Name of Features by measurements on the mean and standard deviation. <H6>
######-Subset the data frame Data by selected names of Features. <H6>

**Uses descriptive activity names to name the activities in the data set.**

######-Read descriptive activity names from activity_labels.txt. <H6>
######-Factorize variable activity in the data frame Data using descriptive activity names. <H6>

**Appropriately labels the data set with descriptive variable names.**

**Creates an independent tidy data set with the average of each variable for each activity and each subject.**

**Final output file is tidydata.txt**
