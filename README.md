# Coursera
# Human Activity Recognition Data Cleaning Project


This repository contains the `run_analysis.R` script that performs the cleaning and tidying of the Samsung Human Activity Recognition data.


## How to use


1. Download and unzip the Samsung data from:  

   https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip


2. Place the unzipped folder `UCI HAR Dataset` inside your working directory or set your R working directory to the folder containing the data.


3. Run the script `run_analysis.R` in R or RStudio.  

   The script will read the data, merge, extract mean and std measurements, apply descriptive activity names, label variables, and create a tidy dataset.


4. The output tidy dataset is saved as `tidy_data.txt`.


## Files included


- `run_analysis.R`: the script performing the analysis.  

- `tidy_data.txt`: the tidy data set output from the script.  

- `CodeBook.md`: documentation describing the variables and transformations.
