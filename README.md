# CleaningSamsungGalaxyS

A full description of the data is available at the site where the data was obtained:

http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

The data for the project are in the archive: "Dataset.zip" or in the directory "Dataset"

The Project does the following to clean data:

It merges the training and the test sets to create one data set. It extracts only the measurements on the mean and standard deviation for each measurement. 
It uses descriptive activity names to name the activities in the data set and appropiately labels the data set with descriptive variable names.
It creates a second, independent tidy data set with the average of each variable for each activity and each subject.

### Steps to reproduce:

Download the Dataset directory or the Dataset.zip (Make sure you have 7-Zip installed on your workstation)
You need the following:
  makeCodebook.Rmd
  run_analysis.Rmd
  run_analysis.r
  Dataset/
  Dataset.zip
  
Open the R script run_analysis.r using a text editor and change the parameter of the setwd function call to your working directory/folder. Run the R script "run_analysis.r". 

It calls the R Markdown file, "run_analysis.Rmd", which contains the bulk of the code along with the Codebook.

(Another alternative would be to clone/fork the repository or download the ZIP file of the entire repository.) 

### Outputs produced:

Tidy dataset file: DatasetHumanActivityRecognitionUsingSmartphones.txt

Codebook file: codebook.md and .html

Output and script: run_analysis.md and html
