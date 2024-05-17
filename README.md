# Driver_Drowsiness_Detection
Driver drowsiness detection is a project built using Dlib and OpenCV with Python as a backend language.

# Logic of project
The project involves direct interaction with both the Dlib library's face detector and the 68 facial landmark detector. The 68 facial landmark detector is an effective and robustly trained detector that identifies the locations on the face that indicate whether or not the eyes are open.

# Working
1) The screenshot above illustrates how the detector is used to identify landmarks.
 
2) At this point, we are calculating the ratio, which is expressed as follows: "Sum of vertical landmark distances divided by twice the horizontal landmark distances."
 
3) At this point, the ratio is entirely reliant on your system, which you may customise to meet the standards for active, drowsy, and sleeping.



![dj](https://github.com/captainaj7/Driver_Drowsiness_Detection/assets/91454482/241486f9-bf56-49d0-a329-8aabd63f7a93)  #oened



