# Human-Activity-Recognition-Tool
INTRODUCTION:
Human Activity Recognition is one of the major advancements in history of computer science since its inception in the utilizing body sensors to detect activities. Latest Smart-Phones are embedded with a wide range of sensors such as accelerometers, gyroscopes and other inertial sensors which help in monitoring the daily activities of a user. The dataset in consideration was extracted by making use of Sensor based Multi-User Activity Recognition, which in short is recognizing activities of different users using on-body sensors.

Due to the inherent noisy nature of the input, pre-processing of the sensor signals by noise filters was done and 128 reading were taken within a window of 2.56 seconds. For each of the window mentioned above, a vector of features along with feature mapping variables like mean, correlation, signal magnitude area and auto regressor coefficients were employed. New set of features such as energy of different frequency bands, frequency skewness and angle between vectors were also employed to improve the learning performance. After the above pre-processing of the data into normalized dataset, a 10299 x 562 dataset (561 regressors) was obtained which will further be split into test and training datasets through which we will test the accuracy of different models in predicting the activity of user based on the 561 features and suggest an efficient model with optimal parameter tuning along with further work that could improve the analysis.
 
DATA DESCRIPTION:
The dataset has been created using inertial data from the smartphone accelerometers and gyroscopes, targeting the recognition of six different activities, classified as:
 Standing-1, Sitting-2, Laying Down-3, Walking-4, Walking Downstairs-5, Walking Upstairs-6 
·      No. of Observations(n): 10299
·      No. of Features(p): 561

Type of Problem: Classification
 
For each record in the dataset the following is provided:
●	Triaxial acceleration from the accelerometer (total acceleration) 
●	Estimated body acceleration.
●	Triaxial Angular velocity from the gyroscope.

These three measurements have been collected in a timed window on each participant multiple times. So, we can say that at an instance of time there are three measurements and then so on for all the time instances. That is how we got such a big matrix of data.
Activity label (Standing, Sitting, Laying Down, Walking, Walking Downstairs, Walking
Upstairs).
