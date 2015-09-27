# Human-Activity-Recognition
README

30 volunteers performed 6 activitys (ALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING) wearing a Smartphone galaxy on their waist to measure movements.

All .txt files read into R. Test and training data merged together.  Test and training data columns are named with features.txt file. Variables corresponding to only mean and standard deviation are extracted.  
Subjects and activity are merged onto existing data frame. Variable names are modified and cleaned-up to be more descriptive. Data set is melted to 4 variables and the average of each variable for each activity and each subject is determined. 
The result is a tidy data set of 180 observations of 81 variables.

See CodeBook.txt to see more information about subjects, activity and variables. 

Below is a schematic of how the data is pieced together. (in pdf file) 
