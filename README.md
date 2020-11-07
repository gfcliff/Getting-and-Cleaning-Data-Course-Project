# Getting-and-Cleaning-Data-Course-Project
# The code performs the following steps:
#downloads the compressed file to the working directory
# uncompresses the archives in the working directory
# builds six data frames from the following files: subject_test.txt; y_test.txt; X_test.txt; subject_train.txt; y_train.txt and X_train.txt.
# builds an additional dataframe with the features.txt file
# name of the variables are assigned for each dataframe. in the case of ... we use features CAMBIAR LOS NOMBRES DE LOS DF A LOS DE LOS ARCHIVOS ORIGINALES PARA NO CONFUNDIR
# we took the decision to relate these DF with these names based on the number of and the description at www.
# for both groups, train and test, a dataframe is built where each observation is identified with an activity and a subject. in order to do so, we bind the columns
# we took the decision to relate these DF with these names based on the number of and the description at www.
# removes the unbinded dataframes
# # We generate a variable to identify whether the subject belongs to the tested or train groups
# builds a unique dataframe where merging the test and train dataframes through the rbind command, adding the observation of one to the other´s. 
# this is possible as both dataframes share the same variables
# removes the unbinded dataframes
# creates a new dataset with a subset of variables (those that contain "Subject" or "Activities" or "mean()" or "std()") in order to extract only the measurements on the mean and standard deviation for each measurement
# generates a new variable that adopts the following values,      , when the "Activities" variable is  respectively. The "Activities" variable is later removed. This is done in order to give descriptive activity names to the activities in the data set. 
# #In order to appropriately label the data set with descriptive variable names, we perform the following changes:
# every word is in lower case
# eliminate "," "_" "-"
# when a "t" is at the beginning of a variable name, it is replaced by "time"
# when a "f" is at the beginning of a variable name, it is replaced by "freq"
# a typo ("bodybody") is corrected
# From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject. tidydta
# the dataframe is saved into tidydta.txt file

