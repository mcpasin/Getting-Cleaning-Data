
This code book describes the structure and variables of the data set "tidy_dataset_with_avg.txt", resulting from executing "run_analysis.R" script

Raw data: https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip 

Full description of the raw data: http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones  

You can easily read the resulting data set using the command read.table:
df<-read.table("tidy_dataset_with_avg.txt")


The resulting data frame is composed of 180 observations (rows) and 88 variables (columns).

There is a total of 30 observations for each subject observed. In total, 6 subjects were observed.

Column 1 "subject": is a numeric identifier of the subject who performed the activity

Column 2 "activity_type": identifies the type of activity performed by the subjects. It's a factor variable and there are 6 possible levels: LAYING, SITTING, STANDING, WALKING, WALKING_DOWNSTAIRS, WALKING_UPSTAIRS.

Columns 3 to 88: these are all numeric variables and represent specific measurements of the subject movements, in terms of mean and standard deviation. 






