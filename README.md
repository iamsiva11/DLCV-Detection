# Object Detection - Deep learning approaches


What is Detection?
The task of assigning a label and a bounding box to all objects in the image 


## Deep learning approaches

An object detection problem can be approached as either a classification problem or a regression problem. 

As a *classification* problem, the image are divided into small patches, each of which will be run through a classifier to determine whether there are objects in the patch. Then the bounding boxes will be assigned to locate around patches that are classified with high probability of present of an object. 

In the *regression* approach, the whole image will be run through a convolutional neural network to directly generate one or more bounding boxes for objects in the images.


### State of art approaches

* Faster R-CNN
* SSD: Single Shot MultiBox Detector
* YOLO: You Only Look Once 	