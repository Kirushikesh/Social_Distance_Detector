# Social Distance Detector
## Table of Content
- [Demo](#demo)
- [Screen Shots](#screen-shots)
- [Overview](#overview)
- [Motivation](#motivation)
- [Technical Aspect](#technical-aspect)
- [Installation](#installation)
- [Run](#run)
- [Directory Tree](#directory-tree)
- [Technologies and Tools](#technologies-and-tools)
- [To Do](#to-do)
- [References](#references)
- [Contact](#contact)
## Demo
## Screen Shots
## Overview
Social Distance Detection using live video feed from camera or from recorded video. This project was developed to suggest social distancing that everyone should follow among one another, reducing close contact, and thereby reducing the spread of a contagious disease (such as coronavirus). YOLOV3(You Only Look Once) pre-trained model is used for person detection. This project calculates different violation limits such as abnormal violation(yellow) and serious violation(red) of social distance. The group of people who violates the limits are joined one another using lines, and total no of violations on a particular frame is calculated. Since the Yolov3.weights cannot be uploaded in github due to size, but can be downloaded in official yolo website.
## Motivation
![image](https://user-images.githubusercontent.com/49152921/119272428-66d45200-bc23-11eb-8e43-867a53b8e18f.png)

As social distance is one of the main criteria to follow in order to avoid spread of contagious disease. It is required to monitor the social distance at the important areas to avoid spreading virus. Since the covid-19 became a deadlier disease to be safe we need to maintain social distance and other precautions.
## Technical Aspect
## Installation
## Run
## Directory Tree
![Screenshot (89)](https://user-images.githubusercontent.com/49152921/119271834-edd3fb00-bc20-11eb-9d8b-43231ff6d7ff.png)

## Technologies and Tools
- Python
- Tensorflow
- YOLO
- Keras
- OpenCV
## To Do
1. Increase the fps by using threads.
2. Transform the arbitary perspective view into bird's eye(top down) view.
3. Adding People Counter.
## References
- [YOLO, YOLOv2 and YOLOv3: All You want to know](https://amrokamal-47691.medium.com/yolo-yolov2-and-yolov3-all-you-want-to-know-7e3e92dc4899#:~:text=YOLOv3%20uses%20a%20new%20network,has%20some%20short%20cut%20connections.&text=After%20training%20on%20classification%20the,is%20removed%20from%20Darknet%2D53.)
- [OpenCV Documentation](https://docs.opencv.org/3.4/db/d30/classcv_1_1dnn_1_1Net.html#a5e74adacffd6aa53d56046581de7fcbd)
- [Landing AI](https://landing.ai/landing-ai-creates-an-ai-tool-to-help-customers-monitor-social-distancing-in-the-workplace/)
- [saimj7 implementation](https://github.com/saimj7/Social-Distancing-Detection-in-Real-Time)
- [pyimagesearch](https://www.pyimagesearch.com/2020/06/01/opencv-social-distancing-detector/)
## Contact
If you found any bug or like to raise a question feel free to contact me through [LinkedIn](https://www.linkedin.com/in/kirushikesh-d-b-10a75a169/). If you feel this project helped you and like to encourage me for more stuffs like this please endorse my skills in my [LinkedIn](https://www.linkedin.com/in/kirushikesh-d-b-10a75a169/) thanks in advance!!!.
