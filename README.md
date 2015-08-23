# Getting and Cleaning Data

## Course Project (Week 3)
Creating one R script called run_analysis.R that does the following.

1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement.
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive activity names.
5. Creates a second, independent tidy data set with the average of each variable for each activity and each subject.

## Steps
1. Download the raw data from https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip
2. Extract data files from zip file downloaded (to the directory where run_analysis.R file is located)
3. From R Studio or R, check/Set the current working directory to the directory where run_analysis.R is located
4. Run the command, source("run_analysis.R")
5. On successful completion, it will generate tidydata.txt file
 
## Related Files
* ___README.md___ - this file
* ___CodeBook.md___ - codebook for this analysis
* ___run_analysis.R___ - the project script
* ___tidydata.txt___ - tidy dataset generated through the run_analysis.R script
