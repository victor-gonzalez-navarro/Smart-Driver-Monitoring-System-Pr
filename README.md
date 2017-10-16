# Smart driver monitoring system using a camera
## IMPORTANT:
```
The file you need to run is called drowsiness_detection.py
```

## Introduction:
The main objective of the project is to predict the driver's state by using a camera. 

This project will focus on detecting drowsiness in the driver. Due to the fact that a common camera cannot analyze with total accuracy in low light scenarios we are going to use an infrared camera. In order to detect the driver drowsiness we will use different methods, first we will focus on analyzing the eyes information like frequency blinking or PERCLOS, then we will analyze other factors like yawning or the movement of the head. Finally we will implement a face recognition system.

## Libraries:
To be able to execute the code you will need to import: numpy, dlib, opencv, math, time and pygame. 
```
import numpy as np
import dlib
import cv2
import math
import time
import pygame
```
## Task list:
- [x] Face detection
- [x] Landmark detection
- [ ] Drowsiness detection
- [ ] Face recognition

## Aditional information:
This project will be modified daily. Not all the optiones are implemented yet, but will be implemented in a future.


