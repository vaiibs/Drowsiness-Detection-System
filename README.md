# Drowsiness-Detection-System

This project implements a real-time drowsiness detection system using Python, OpenCV, Dlib, and facial landmarks. The system tracks facial features, specifically eye movements, to classify the user’s state as Active, Drowsy, or Sleeping. 

This can be used in applications like driver fatigue monitoring and workplace safety systems.

The 68-landmark detector data (.dat) file can be found (https://github.com/GuoQuanhao/68_points/blob/master/shape_predictor_68_face_landmarks.dat)

How It Works

    Face Detection: Uses Dlib's pre-trained face detector to locate faces in the video frame.
    
    Landmark Detection: Detects 68 facial landmarks to pinpoint eye positions.
    
    Eye Aspect Ratio (EAR): Calculates the ratio of vertical to horizontal distances of eye 
                            landmarks to determine the eye's state.
    Status Classification:
                        Sleeping: Eyes closed for a prolonged duration.
                        Drowsy: Partially closed eyes detected consistently.
                        Active: Eyes open and blinking normally.


Technologies Used

    OpenCV: For image processing and video capture.
    Dlib: For face detection and facial landmark identification.
    Numpy: For efficient numerical computations.
    Imutils: For additional image processing utilities.

 ![image](https://github.com/user-attachments/assets/5d35ea85-785f-412c-82bc-3ea95e533c59)


![image](https://github.com/user-attachments/assets/86c17663-550c-48af-af67-b81b4f421498)


![image](https://github.com/user-attachments/assets/885169e1-31da-458d-b6a0-9cd22cc90a93)


