# spanish-sign-language-db

###This data set was created for performing experiments for involving gesture recognition.

The format of data is comma-separated values. The data was captured using the Leap Motion sensor, which provides 3D data of hand position, and a program implemented in Java, to be released shortly.

There are 2 folders: 
- separated_gestures: a data set of 91 different gestures. Each gesture has 40 samples. In total, there are 3640 files.

- consecutive_gestures: a data set of consecutives gestures. Each file contains data of a single sentence in Spanish sign language. There are 274 files. 

In each file there are 42 columns corresponding to different time-dependent variables. For each hand there are 21 variables which provide 3D information. 

The variables are the following:
  1. The X-component of the direction from the left-palm position toward the fingers. 
  2. The Y-component of the direction from the left-palm position toward the fingers.
  3. The Z-component of the direction from the left-palm position toward the fingers.
  4. Pitch of the left hand.
  5. Roll of the left hand.
  6. Yaw of the left hand.
  7. The direction of the left thumb in X axis.
  8. The direction of the left thumb in Y axis.
  9. The direction of the left thumb in Z axis.
  10. The direction of the left index finger in X axis.
  11. The direction of the left index finger in Z axis.
  12. The direction of the left index finger in Z axis.
  13. The direction of the left middle finger in X axis.
  14. The direction of the left middle finger in Z axis.
  15. The direction of the left middle finger in Z axis.
  16. The direction of the left ring finger in X axis.
  17. The direction of the left ring finger in Z axis.
  18. The direction of the left ring finger in Z axis.
  19. The direction of the pinky in X axis.
  20. The direction of the pinky in Y axis.
  21. The direction of the pinky in Z axis.
  22. The X-component of the direction from the right-palm position toward the fingers. 
  23. The Y-component of the direction from the right-palm position toward the fingers.
  24. The Z-component of the direction from the right-palm position toward the fingers.
  25. Pitch of the right hand.
  26. Roll of the right hand.
  27. Yaw of the right hand.
  28. The direction of the right thumb in X axis.
  29. The direction of the right thumb in Y axis.
  30. The direction of the right thumb in Z axis.
  31. The direction of the right index finger in X axis.
  32. The direction of the right index finger in Y axis.
  33. The direction of the right index finger in Z axis.
  34. The direction of the right middle finger in X axis.
  35. The direction of the right middle finger in Y axis.
  36. The direction of the right middle finger in Z axis.
  37. The direction of the right ring finger in X axis.
  38. The direction of the right ring finger in Y axis.
  39. The direction of the right ring finger in Z axis.
  40. The direction of the right pinky in X axis.
  41. The direction of the right pinky in Y axis.
  42. The direction of the right pinky in Z axis.
  
The sample frequency is fixed at 30 frames per second. All data is normalised between [0,1]. When a gesture is performed with only one hand (right hand always) the data of one hand is duplicated. This is because the data was used in the HTK toolkit and when some gesture was performed with only one hand, the other part of the feature matrix was filled with a default value: 0. In this event, HTK detects the data as too similar and refuses to train the models.


## This data is not allowed for commercial purposes! 
## Please, if you use any part of the corpus in your own work, cite the following article:
Soon
