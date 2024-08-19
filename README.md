# Face-Detection-Using-OpenCV
This project demonstrates real-time face detection using OpenCV's Haar Cascade Classifier. The script captures video from a webcam, processes each frame to detect faces, and highlights them with rectangles.

#Features:
1. Real-time Face Detection: Detects faces in a live video stream using the Haar Cascade method. 
2. OpenCV Implementation: Utilizes OpenCV's powerful image processing capabilities. 
3. Customizable Parameters: Adjust detection parameters like scaleFactor, minNeighbors, and minSize for optimized performance. 

#Requirements:
Python 3.x , 
OpenCV 4.x

#File Details:
1. face.py: Main script that handles video capture, face detection, and displaying results. 
2. haarcascade_frontalface_default.xml: Pre-trained XML classifier for detecting faces (ensure the correct path to this file is specified in the script).

#Notes:
1. Ensure that the Haar Cascade XML file is correctly located and that the script points to its exact path. 
2. Modify the detection parameters to improve accuracy based on your specific use case.
