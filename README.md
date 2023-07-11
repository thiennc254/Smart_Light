# SmartLight
Bedroom light system that read the user face to recognize their behaviour and adapt accordingly
# Requiremnt
## Hardware
  `Kit ESP32`
  5 LED
  Camera
## Software
  Download file [*shape_predictor_68_face_landmarks*](http://dlib.net/files/)
  Arduino IDF for ESP32
  opencv
  paho-mqtt
  dlib
  scpicy
  imutils
  threading
  numpy
  broker
# Run command:
## Test algorithms: 
  python FacialLandmarks.py
## Main Program: 
  python EyesClosedTracking.py
