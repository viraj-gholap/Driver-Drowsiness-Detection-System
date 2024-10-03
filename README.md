# Driver Drowsiness Detection System

## Mini Project on “Driver Drowsiness Detection System” as the partial fulfillment for the requirement of Second Year of Engineering (4th Semester) in S.E. - Information Technology during the academic year 2020-2021.


### Proposed System
The “haar cascade files” folder consists of the xml files that are needed to detect objects from the image. In our case, we are detecting the face and eyes of the person.The models folder contains our model file “cnnCat2.h5” which was trained on convolutional neural networks.We have an audio clip “alarm.wav” which is played when the person is feeling drowsy.“Model.py” file contains the program through which we built our classification model by training on our dataset. You could see the implementation of convolutional neural network in this file.“Drowsiness detection.py” is the main file of our project. 

To start the detection procedure, we have to run this file.

Step 1 – Take image as input from a camera.

Step 2 – Detect the face in the image and create a Region of Interest (ROI).

Step 3 – Detect the eyes from ROI and feed it to the classifier.

Step 4 – Classifier will categorize whether eyes are open or closed. 

Step 5 – Calculate score to check whether the person is drowsy


### The requirement for this Python project is a webcam through which we will capture images. 

You need to have Python (3.6 version recommended) installed on your system, then using pip, 
you can install the necessary packages.

1.OpenCV – pip install opencv-python (face and eye detection). 

2.TensorFlow – pip install tensorflow (keras uses TensorFlow as backend). 

3.Keras – pip install keras (to build our classification model).

4.Pygame – pip install pygame (to play alarm sound).
