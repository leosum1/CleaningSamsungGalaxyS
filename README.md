# CleaningSamsungGalaxyS

A full description of the data is available at the site where the data was obtained:

http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

The data for the project are in the archive: Dataset.zip

The R script called run_analysis.R does the following:

It merges the training and the test sets to create one data set. It extracts only the measurements on the mean and standard deviation for each measurement. It uses descriptive activity names to name the activities in the data set.
It creates a second, independent tidy data set with the average of each variable for each activity and each subject.

### Steps to reproduce:

Open the R script run_analysis.r using a text editor and change the parameter of the setwd function call to your working directory/folder.

Run the R script run_analysis.r. 

It calls the R Markdown file, run_analysis.Rmd, which contains the bulk of the code.

### Outputs produced:

Tidy dataset file DatasetHumanActivityRecognition.txt

Codebook file codebook.md
