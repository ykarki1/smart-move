# smart-move
Machine Learning Project on Smartphone Activity Detector
We built some machine learning models to recognize the human activity with the help of sensor readings of the phone being carried. **all_models.ipynb** is the main file where all the models are compiled.





## Dataset
Source of the dataset was [UCI Machine Learning Repository](http://archive.ics.uci.edu/ml/datasets/Smartphone-Based+Recognition+of+Human+Activities+and+Postural+Transitions#). Data set built from the recordings of 30 subjects performing basic activities and postural transitions while carrying a waist-mounted smartphone (Samsung Galaxy S II) with embedded inertial sensors (accelerometer and gyroscope).
Dataset was already cleaned, scaled and split into training and testing data. As features the dataset has 561 datapoints for each instance of activity.
And as labels, activities composed of six basic activities: three static postures (standing, sitting, lying) and three dynamic activities (walking, walking downstairs and walking upstairs). The experiment also included postural transitions that occurred between the static postures. These are: stand-to-sit, sit-to-stand, sit-to-lie, lie-to-sit, stand-to-lie, and lie-to-stand. These all activities were labeled with a number as following:

1. WALKING           
2. WALKING_UPSTAIRS  
3. WALKING_DOWNSTAIRS
4. SITTING           
5. STANDING          
6. LAYING            
7. STAND_TO_SIT      
8. SIT_TO_STAND      
9. SIT_TO_LIE        
10. LIE_TO_SIT        
11. STAND_TO_LIE      
12. LIE_TO_STAND


## Result 
We created some models with scikit learn and tensorflow keras. Out of all the models, support vector machine linear and deep neural network seem promising with test accuracy of 95.2% and 94.3% respectively.
![Summary graph of all models](https://github.com/ykarki1/smart-move/blob/master/KNN%20Results%20screenshots/Screen%20Shot%202019-08-05%20at%201.19.55%20PM.png?raw=true)

