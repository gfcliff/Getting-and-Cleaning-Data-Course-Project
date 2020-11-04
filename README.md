# Getting-and-Cleaning-Data-Course-Project
# The code performs the following steps:
#downloads the compressed file to the working directory
# uncompresses the archives in the working directory
# builds six data frames from the following files: subject_test.txt; y_test.txt; X_test.txt; subject_train.txt; y_train.txt and X_train.txt.
# builds an additional dataframe with the features.txt file
# name of the variables are assigned for each dataframe. in the case of ... we use features CAMBIAR LOS NOMBRES DE LOS DF A LOS DE LOS ARCHIVOS ORIGINALES PARA NO CONFUNDIR
# we took the decision to relate these DF with these names based on the number of and the description at www.
# for both groups, train and test, we build a dataframe where each observation is identified with an activity and a subject. in order to do so, we bind the columns
# we took the decision to relate these DF with these names based on the number of and the description at www.
# we remove the unbinded dataframes
# we build a unique dataframe where merging the test and train dataframes through the rbind command, adding the observation of one to the other´s. 
# this is possible as both dataframes share the same variables
# we remove the unbinded dataframes
