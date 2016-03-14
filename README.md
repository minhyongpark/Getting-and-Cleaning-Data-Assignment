
## Getting and Cleaning Data Project

Min Park

Repo w/ assignment work and submission

### Overview
This project serves to demonstrate student's ability to create a tidy data set that can be used for subsequent
analysis. 

More about the data used for the project can be found here [The UCI Machine Learning Repository](http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones)

[The source data for this project can be found here.](https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip)

### Main script
run_analysis.R - takes inputs from zip file above and creates a tidy dataset after combining testing and training sets.  Specifically:
1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement. 
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive activity names. 
5. Creates a second, independent tidy data set with the average of each variable for each activity and each subject. 

### Additional Information
Additional information about variables can be found in CodeBook.MD file.
