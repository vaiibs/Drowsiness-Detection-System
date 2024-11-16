# Drowsiness-Detection-System

This project implements a real-time drowsiness detection system using Python, OpenCV, Dlib, and facial landmarks. The system tracks facial features, specifically eye movements, to classify the user’s state as Active, Drowsy, or Sleeping. 

This can be used in applications like driver fatigue monitoring and workplace safety systems.

How It Works

    Face Detection: Uses Dlib's pre-trained face detector to locate faces in the video frame.
    Landmark Detection: Detects 68 facial landmarks to pinpoint eye positions.
    Eye Aspect Ratio (EAR): Calculates the ratio of vertical to horizontal distances of eye landmarks to determine the eye's state.
    Status Classification:
    Sleeping: Eyes closed for a prolonged duration.
    Drowsy: Partially closed eyes detected consistently.
    Active: Eyes open and blinking normally.


Technologies Used

    OpenCV: For image processing and video capture.
    Dlib: For face detection and facial landmark identification.
    Numpy: For efficient numerical computations.
    Imutils: For additional image processing utilities.

  
