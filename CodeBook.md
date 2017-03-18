# Codebook course project getting and cleaning data

The R script run_analysis.R does the following:
      
      1. It downloads and unzips the data found in 
      https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip
      2. It merges the training and the test sets to create one data set.
      3. It extracts only the measurements on the mean and standard deviation for each measurement.
      4. It uses descriptive activity names to name the activities in the data set.
      5. It appropriately labels the data set with descriptive variable names.
      6.	From the data set in step 5, it creates an tidy data set with the average of each variable for 
      each activity and each subject.
      
### Variables:

      •	x_train, y_train, x_test, y_test, subject_train and subject_test contain the data from 
      the downloaded files.
      •	mrg_train, mrg_test and AllData merge the previous datasets to further analysis.
