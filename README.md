# Course Project: Getting and Cleaning Data

This is the course project for the Getting and Cleaning Data course in the Data science specialization of Coursera.
The R script, `run_analysis.R`, does the following:

1. Download the dataset if it does not exist yet in the working directory
2. Load the activity and feature information
3. Loads both the training and test datasets, keeping only the columns which reflect a mean or standard deviation
4. Loads the activity and subject data for each dataset, and merges those columns with the dataset
5. Merges the two datasets into one
6. Converts the `activity` and `subject` columns into factors
7. Creates a tidy dataset that consists of the average (mean) value of each
   variable for each subject and activity pair.

The end result is the file `tidyData.txt`.
