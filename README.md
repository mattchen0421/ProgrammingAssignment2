code book  
"subject" is the code of the subjects.  
"activity" lable the six activities that subject done  
X,Y,Z represent 3 differnt directon  
.mean means it is a mean value  
.std means it is a standard diviation  
 What the variable have record is written in the name of variable,  
 "BodyGyroscope""BodyAccelerometer" etc.  
 All the variables are num except "activity"  
All the variables' names are list beneath.  

"subject"                                           
"activity"                                          
"TimeBodyAccelerometer.mean...X"                    
"TimeBodyAccelerometer.mean...Y"                    
"TimeBodyAccelerometer.mean...Z"                    
"TimeGravityAccelerometer.mean...X"                 
"TimeGravityAccelerometer.mean...Y"                 
"TimeGravityAccelerometer.mean...Z"                 
"TimeBodyAccelerometerJerk.mean...X"                
"TimeBodyAccelerometerJerk.mean...Y"                
"TimeBodyAccelerometerJerk.mean...Z"                
"TimeBodyGyroscope.mean...X"                        
"TimeBodyGyroscope.mean...Y"                        
"TimeBodyGyroscope.mean...Z"                        
"TimeBodyGyroscopeJerk.mean...X"                    
"TimeBodyGyroscopeJerk.mean...Y"                    
"TimeBodyGyroscopeJerk.mean...Z"                    
"TimeBodyAccelerometerMagnitude.mean.."             
"TimeGravityAccelerometerMagnitude.mean.."          
"TimeBodyAccelerometerJerkMagnitude.mean.."         
"TimeBodyGyroscopeMagnitude.mean.."                 
"TimeBodyGyroscopeJerkMagnitude.mean.."             
"FrequencyBodyAccelerometer.mean...X"               
"FrequencyBodyAccelerometer.mean...Y"               
"FrequencyBodyAccelerometer.mean...Z"               
"FrequencyBodyAccelerometer.meanFreq...X"           
"FrequencyBodyAccelerometer.meanFreq...Y"           
"FrequencyBodyAccelerometer.meanFreq...Z"           
"FrequencyBodyAccelerometerJerk.mean...X"           
"FrequencyBodyAccelerometerJerk.mean...Y"           
"FrequencyBodyAccelerometerJerk.mean...Z"           
"FrequencyBodyAccelerometerJerk.meanFreq...X"       
"FrequencyBodyAccelerometerJerk.meanFreq...Y"       
"FrequencyBodyAccelerometerJerk.meanFreq...Z"       
"FrequencyBodyGyroscope.mean...X"                   
"FrequencyBodyGyroscope.mean...Y"                   
"FrequencyBodyGyroscope.mean...Z"                   
"FrequencyBodyGyroscope.meanFreq...X"               
"FrequencyBodyGyroscope.meanFreq...Y"               
"FrequencyBodyGyroscope.meanFreq...Z"               
"FrequencyBodyAccelerometerMagnitude.mean.."        
"FrequencyBodyAccelerometerMagnitude.meanFreq.."    
"FrequencyBodyAccelerometerJerkMagnitude.mean.."    
"FrequencyBodyAccelerometerJerkMagnitude.meanFreq.."
"FrequencyBodyGyroscopeMagnitude.mean.."            
"FrequencyBodyGyroscopeMagnitude.meanFreq.."        
"FrequencyBodyGyroscopeJerkMagnitude.mean.."        
"FrequencyBodyGyroscopeJerkMagnitude.meanFreq.."    
"Angle.TimeBodyAccelerometerMean.Gravity."          
"Angle.TimeBodyAccelerometerJerkMean..GravityMean." 
"Angle.TimeBodyGyroscopeMean.GravityMean."          
"Angle.TimeBodyGyroscopeJerkMean.GravityMean."      
"Angle.X.GravityMean."                              
"Angle.Y.GravityMean."                              
"Angle.Z.GravityMean."                              
"TimeBodyAccelerometer.std...X"                     
"TimeBodyAccelerometer.std...Y"                     
"TimeBodyAccelerometer.std...Z"                     
"TimeGravityAccelerometer.std...X"                  
"TimeGravityAccelerometer.std...Y"                  
"TimeGravityAccelerometer.std...Z"                  
"TimeBodyAccelerometerJerk.std...X"                 
"TimeBodyAccelerometerJerk.std...Y"                 
"TimeBodyAccelerometerJerk.std...Z"                 
"TimeBodyGyroscope.std...X"                         
"TimeBodyGyroscope.std...Y"                         
"TimeBodyGyroscope.std...Z"                         
"TimeBodyGyroscopeJerk.std...X"                     
"TimeBodyGyroscopeJerk.std...Y"                     
"TimeBodyGyroscopeJerk.std...Z"                     
"TimeBodyAccelerometerMagnitude.std.."              
"TimeGravityAccelerometerMagnitude.std.."           
"TimeBodyAccelerometerJerkMagnitude.std.."          
"TimeBodyGyroscopeMagnitude.std.."                  
"TimeBodyGyroscopeJerkMagnitude.std.."              
"FrequencyBodyAccelerometer.std...X"                
"FrequencyBodyAccelerometer.std...Y"                
"FrequencyBodyAccelerometer.std...Z"                
"FrequencyBodyAccelerometerJerk.std...X"            
"FrequencyBodyAccelerometerJerk.std...Y"            
"FrequencyBodyAccelerometerJerk.std...Z"            
"FrequencyBodyGyroscope.std...X"                    
"FrequencyBodyGyroscope.std...Y"                    
"FrequencyBodyGyroscope.std...Z"                    
"FrequencyBodyAccelerometerMagnitude.std.."         
"FrequencyBodyAccelerometerJerkMagnitude.std.."     
"FrequencyBodyGyroscopeMagnitude.std.."             
"FrequencyBodyGyroscopeJerkMagnitude.std.."  

How scripts work:  
first import all the dataframe  
than bind the train data and test data together  
than put subject code and the value together  
than select the variables contain "mean" and "std"  
than transfer the code of "activity" to real names  
than change all the abbreviation in the variable into non-abbreviated discription  
than create a new dataframe contains average of each variable for each activity and each subject  
last export the dataframe with write.table  
