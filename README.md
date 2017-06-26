#code book
=================

The data comes from the accelerometer and gyroscope 3-axial raw signals timeAcc-XYZ and timeGyro-XYZ. These time domain signals were captured at a constant rate of 50 Hz. Then they were filtered using a median filter and a 3rd order low pass Butterworth filter with a corner frequency of 20 Hz to remove noise. Similarly, the acceleration signal was then separated into body and gravity acceleration signals (timeBodyAcc-XYZ and timeGravityAcc-XYZ) using another low pass Butterworth filter with a corner frequency of 0.3 Hz. 

Subsequently, the body linear acceleration and angular velocity were derived in time to obtain Jerk signals (timeBodyAccJerk-XYZ and timeBodyGyroJerk-XYZ). Also the magnitude of these three-dimensional signals were calculated using the Euclidean norm (timeBodyAccMag, timeGravityAccMag, timeBodyAccJerkMag, timeBodyGyroMag, timeBodyGyroJerkMag). 

Finally a Fast Fourier Transform (FFT) was applied to some of these signals producing freqBodyAcc-XYZ, freqBodyAccJerk-XYZ, freqBodyGyro-XYZ, freqBodyAccJerkMag, freqBodyGyroMag, freqBodyGyroJerkMag. 

These signals were used to estimate variables of the feature vector for each pattern:  
'-XYZ' is used to denote 3-axial signals in the X, Y and Z directions.

*timeBodyAcc-XYZ
*timeGravityAcc-XYZ
*timeBodyAccJerk-XYZ
*timeBodyGyro-XYZ
*timeBodyGyroJerk-XYZ
*timeBodyAccMag
*timeGravityAccMag
*timeBodyAccJerkMag
*timeBodyGyroMag
*timeBodyGyroJerkMag
*freqBodyAcc-XYZ
*freqBodyAccJerk-XYZ
*freqBodyGyro-XYZ
*freqBodyAccMag
*freqBodyAccJerkMag
*freqBodyGyroMag
*freqBodyGyroJerkMag

The set of variables that were estimated from these signals are: 

*Mean: Mean value

*Std: Standard deviation

activity: 6 modes: WALKING,WALKING_UPSTAIRS,WALKING_DOWNSTAIRS,SITTING,STANDING,LAYING	.

subject: number 1:30, representing each of 30 subjects tested. 	
