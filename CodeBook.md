##Getting and Cleaning Data:CodeBook for tidyData

Min Park

###Attribute Information:

For each record in the dataset it is provided: 
- Triaxial acceleration from the accelerometer (total acceleration) and the estimated body acceleration. 
- Triaxial Angular velocity from the gyroscope. 
- A 561-feature vector with time and frequency domain variables. 
- Its activity label. 
- An identifier of the subject who carried out the experiment.

###Identifier fields
"subjectId"         person ID
"activityId"        activity ID for person              
          
###Measurements

####Seconds:
"timeBodyAccMagnitudeMean"       
"timeBodyAccMagnitudeStdDev"      

"timeGravityAccMagnitudeMean"     
"timeGravityAccMagnitudeStdDev"  

"timeBodyAccJerkMagnitudeMean"    
"timeBodyAccJerkMagnitudeStdDev"  

"timeBodyGyroMagnitudeMean"      
"timeBodyGyroMagnitudeStdDev"     

"timeBodyGyroJerkMagnitudeMean"   
"timeBodyGyroJerkMagnitudeStdDev"

####Counts:
"freqBodyAccMagnitudeMean"        
"freqBodyAccMagnitudeStdDev"     

"freqBodyAccJerkMagnitudeMean"   
"freqBodyAccJerkMagnitudeStdDev"  

"freqBodyGyroMagnitudeMean"       
"freqBodyGyroMagnitudeStdDev"    

"freqBodyGyroJerkMagnitudeMean"   
"freqBodyGyroJerkMagnitudeStdDev" 

####Characteristics
"activityType"      String. Walking, sitting, standing, etc.
