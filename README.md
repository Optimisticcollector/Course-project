The goal of this project is to create R script that does the following:

1. Merges the training and the test sets to create one data set
2. Extracts only the measurements on the mean and standard deviation for each measurement
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive variable names.
5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

How does it work?

1. The training and the test sets are merged into x(measurements), y(activity) and subject respectively.
2. The data measurements are loaded, extra columns ("-mean", "-std") are added
3. Data sets are extracted by columns "-mean", "-std"
4. Variable names are modified to descriptive (symbols like (,),- are removed; "-mean", "-std" are replaced by "Mean", "Std")
5. Tidy dataset is generated (for details see Tidy data set.txt)