# Face_eye_detection_using_opencv Through Webcam
Opencv is used in this implementation to identify the face and eye using  haarcascade_frontalface_default.xml and haarcascade_eye.xml files
# Prerequisite
- Open Github and download opencv project(location where you will get both above listed project i will attach a screen shot for identtifying th algorithms link of that file: https://github.com/opencv/opencv
  - once you have downloaded the project open data folder in it and choose facedetect and eyedetect xml file
  - import cv2 in the ide you are working i have done it in jupter notebook
  - Then import few other Packages listed below
    - import numpy as np
    - import time
    - import matplotlib.pyplot as plt
  - once all imports are done Provide Path of both the xml files for face and eyes which are present in data folder of opencv project which          you downloaded from github
    - cv2.VideoCapture(0) this will give peremession to use webcam. 0 as argument here means device(web camp) it can vary on your system if it gives error with 0 feel free to try 1 there you are almost done follow up the rest code and run your program to check results
 # Screenshot of xml file you will be using for this project
 ![ss](https://user-images.githubusercontent.com/42214175/70682505-184c2580-1cc5-11ea-9709-47a2a265b345.jpg)
  
