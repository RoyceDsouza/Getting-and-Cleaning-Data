# Getting-and-Cleaning-Data
Week 3 Course Project: Data Science - Getting and Cleaning Data 

Steps on how run_analysis.R script works.

Step1: Unzip the data from https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip and rename the folder with "data".

Step 2: Make sure the folder "data" and the run_analysis.R script are both in the current working directory.

Step 3: Use source("run_analysis.R") command in RStudio.

Step 4: Two output files are generated in the current working directory:file 1 is called merged_data.txt it contains a data frame called cleanedData with 10299*68 dimension and file 2 is called data_with_means.txt which contains a data frame called result with 180*68 dimension.

Step 5: Finally, use data <- read.table("data_with_means.txt") command in RStudio to read the file. 

Reading the Output: We are required to get the average of each variable for each activity and each subject, and there are 6 activities in total and 30 subjects in total, we have 180 rows with all combinations for each of the 66 features.
