# Live Social Distancing Tracker Using Python And OpenCV

This project is developed for live detection and tracking of social distancing during the wake of novel Corona-virus. The code in this project uses TensorFlow and OpenCV in Python to check if social distancing measures are followed by the citizens or not.

### This project is inspired from the works of Landing AI and Airpix.

![banner](output.gif)

## Technologies Required
1. OpenCV 3.0 (or above)
2. TensorFlow 1.5 (or above)
3. Python 3.5 (or above)
###### (Please Note: If your machine supports GPU operations, then using TensorFlow GPU version is advised and recommended for better results)

## Getting Started

1. Make sure you have installed all the above mentioned technologies on your machine.
2. Create a folder for this project.
3. Clone this repository on your local machine.
4. Download COCO trained-model from [here](https://github.com/tensorflow/models/blob/master/research/object_detection/g3doc/detection_model_zoo.md) and extract it. For this project, I have used "faster_rcnn_inception_v2_coco". You can change the model depending on your computing resources. 
5. Update the paths to model and and input video in the code. (Use 0 to start real-time streaming through webcam)
6. Move to the project directory and run the Python file. The output will be displayed. Press 'Esc' to stop execution.

###### (Please Note: If you are using TensorFlow 1.x (where x>=5) then change to "import tensorflow as tf" in the code)

## Testing Environment

1. Laptop Specifications : Intel(R) Core(TM) i5-7200U (upto 2.7GHz), 8 GB RAM
2. Operating System      : Ubuntu 18.04
3. Python version        : Python 3.7.6
4. Tensorflow version    : 2.2.0 
5. OpenCV version        : 4.2.0     
6. Input Video           : [TownCentreXVID.avi](http://www.robots.ox.ac.uk/~lav/Research/Projects/2009bbenfold_headpose/project.html)


## References

1. [TensorFlow Object Detection API](https://github.com/tensorflow/models/tree/master/research/object_detection) is a great start to detect objects of different categories alongwith their scores.
2. The video used for testing purpose is referenced from [Course Gaze Estimation In Visual Surveillance Project](http://www.robots.ox.ac.uk/~lav/Research/Projects/2009bbenfold_headpose/project.html).
