# spanish-sign-language-db

###This data set was created for make experiments for gesture recognition.

The format of data is comma-separated values. The data was captured using Leap Motion sensor and a program implemented in Java.

There are 2 folders: 
- separated_gestures: data set of 91 different gestures. Each gesture has 40 samples. In total, there are 3640 files.

- consecutive_gestures: data set of consecutives gestures. Each file contains data of sentence in Spanish sign language. There are 274 files. 

In each file are 42 columns correspond to different time-dependent variables. For each hand are 21 variables which give 3D information. 

The variables are the following:
  1. The direction from the palm position toward the fingers in X axis of the left hand.
  2. The direction from the palm position toward the fingers in Y axis of the left hand.
  3. The direction from the palm position toward the fingers in Z axis of the left hand.
  4. Pitch of the left hand.
  5. Roll of the left hand.
  6. Yaw of the left hand.
  7. The direction of left thumb in X axis.
  8. The direction of left thumb in Y axis.
  9. The direction of left thumb in Z axis.
  10. The direction of left index finger in X axis.
  11. The direction of left index finger in Z axis.
  12. The direction of left index finger in Z axis.
  13. The direction of left middle finger in X axis.
  14. The direction of left middle finger in Z axis.
  15. The direction of left middle finger in Z axis.
  16. The direction of left ring finger in X axis.
  17. The direction of left ring finger in Z axis.
  18. The direction of left ring finger in Z axis.
  19. The direction of pinky in X axis.
  20. The direction of pinky in Y axis.
  21. The direction of pinky in Z axis.
  22. The direction from the palm position toward the fingers in X axis.
  23. The direction from the palm position toward the fingers in Y axis.
  24. The direction from the palm position toward the fingers in Z axis.
  25. Pitch of the right hand.
  26. Roll of the right hand.
  27. Yaw of the right hand.
  28. The direction of left thumb in X axis.
  29. The direction of left thumb in Y axis.
  30. The direction of left thumb in Z axis.
  31. The direction of left index finger in X axis.
  32. The direction of left index finger in Y axis.
  33. The direction of left index finger in Z axis.
  34. The direction of left middle finger in X axis.
  35. The direction of left middle finger in Y axis.
  36. The direction of left middle finger in Z axis.
  37. The direction of left ring finger in X axis.
  38. The direction of left ring finger in Y axis.
  39. The direction of left ring finger in Z axis.
  40. The direction of pinky in X axis.
  41. The direction of pinky in Y axis.
  42. The direction of pinky in Z axis.
  
The image capture rate is fixed at 30 frames per second. All data is normalised between [0,1]. When a gesture is made with only one hand (right hand always) the data of one hand is duplicated. This is because the data was used in HTK tool and when some gesture was made with only one hand, the other part of matrix was filled by default value: 0. This induced that the data was to similar and HTK could not train the models.


## This data is not allowed for commercial purposes! 
##PLEASE, if you will publish making use of this data, cite the following article:

