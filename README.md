# Social-Distancing-Detector [![License: MIT](https://camo.githubusercontent.com/a307f74a14e41e762300323414ddef81f3d53ae2/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f6c6963656e73652f736f757263657265722d696f2f736f757263657265722d6170702e7376673f636f6c6f72423d666630303030)](https://github.com/ParthPathak27/Social-Distancing-Detector/blob/master/LICENSE)
An AI Tool to Help Customers Monitor Social Distancing in the Workplace.

### Sourcerer Mohan Morkel https://www.linkedin.com/in/mohanmorkel/

Demo is here : https://www.youtube.com/watch?v=ZKJwJv7iVRE


In the fight against the coronavirus, social distancing has proven to be a very effective measure to slow down the spread of the disease. While millions of people are staying at home to help flatten the curve, many customers in the manufacturing and pharmaceutical industries are still having to go to work everyday to make sure our basic needs are met.

To help ensure social distancing protocol in their workplace, I have developed an AI-enabled social distancing detection tool that can detect if people are keeping a safe distance from each other by analyzing real time video streams from the camera.

The demos below will help to visually explain our approach that consists of three main steps:

1. Detect the humans in the frame with yolov3 convolutional neural network.
2. Calculate the distance between all the instances of humans detected in the frame.
3. Classify the determined distances as 'Alert' or 'Ok' for social distancing.

### Output (Image)
![screenshot](https://github.com/ParthPathak27/Social-Distancing-Detector/blob/master/output.jpg)

### Output (Video)
This demo video is performed on the public “OXFORD TOWN CENTRE” dataset

![This demo video is performed on the public “OXFORD TOWN CENTRE” dataset](https://github.com/ParthPathak27/Social-Distancing-Detector/blob/master/output.gif)


### Requirements:

1. Numpy
2. Time
3. OpenCV
4. OpenCV_Contrib
5. Math

Download yolov3.weights for COCO dataset from this link and add it to your repo, [click here](https://pjreddie.com/darknet/yolo/)

### Installation of Model:

* To deploy algorithm on images, python SDD_Image.py
* To deploy algorithm on videos, python SDD_Video.py
* To deploy algorithm on live streaming webcam, python SDD_Camera.py


Reference: https://landing.ai/landing-ai-creates-an-ai-tool-to-help-customers-monitor-social-distancing-in-the-workplace/
