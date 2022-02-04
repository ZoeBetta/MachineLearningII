# MachineLearningII
For this Machine Learning assignment I have used the dataset at the following link: https://www.kaggle.com/uciml/wall-following-robot  
This dataset stores the readings from ultrasound sensors of a mobile robot moving in a room using the behaviour follow the wall.  
There are three sets of data: one with the entire sets of 24 readings from the sensors, one with 4 simplifies readings from the sensors and one with two simplified reading from the sensors.  
For more information please go the link provided above.   
For each dataset I added a line on top of the csv file to add the labels for each columns.  
From the reading of the sensor the goal was to retrieve the actual motion state of the robot:  
-move forward  
-sharp turn right  
-slight turn left  
-slight turn right.  
For the code I implemented it on colab using the sklearn library.
