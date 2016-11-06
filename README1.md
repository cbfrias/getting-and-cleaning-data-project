
# This is the course project for Getting and Cleaning Data course on Coursera. Source file is run_analysis.R, which does the following things: <h1>


# Download the dataset if it does not already exist in the working directory.  <h2>
-Check if zip has already been downloaded 
-Check if zip has already been unzipped

# Load activity, subject and feature info. Read data from the files into the variables. <h2>
-Read the Activity files. 
-Read the Subject files. 
-Read Features files.

# Merges the training and the test sets to create one data set. <h2>
-Concatenate the data tables by rows. 
-set names to variables. 
-Merge columns to get the data frame Data for all data.

# Extracts only the measurements on the mean and standard deviation for each measurement. <h2>
-Subset Name of Features by measurements on the mean and standard deviation. 
-Subset the data frame Data by selected names of Features.

# Uses descriptive activity names to name the activities in the data set. <h2>
-Read descriptive activity names from activity_labels.txt 
-Factorize variable activity in the data frame Data using descriptive activity names.

# Appropriately labels the data set with descriptive variable names. <h2>

# Creates an independent tidy data set with the average of each variable for each activity and each subject. <h2>

# Final output file is tidydata.txt <h2>
