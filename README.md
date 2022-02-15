# Selected Topics in Visual Recognition using Deep Learning
This repository is the implementation of the challenges for IOC5008 Selected Topics in Visual Recognition using Deep Learning course in 2021 Fall semester at National Yang Ming Chiao Tung University.

## Bird Image Classification
We participate a bird image classification challenge hosted on CodaLab. This challenge provided a total of 6,033 bird images (3000 for training and 3033 for testing) belonging to 200 bird species.

Testing Accuracy:
* EfficientNet-b4 w/o sched: 55.29%
* EfficientNet-b4 with sched: 72.53%

[[report](https://github.com/joycenerd/bird-images-classification/blob/main/REPORT.pdf)] [[code](https://github.com/joycenerd/bird-images-classification)]

## Street View House Numbers Detection
We participate in the SVHN detection competition hosted on CodaLab. The Street View House Numbers (SVHN) dataset contains 33,402 training images and 13,068 testing images. We are required to train not only an accurate but fast digit detector. The submission format should follow COCO results. To test the detection model's speed, we must benchmark the detection model in the Google Colab environment and screenshot the results. 

Testing mAP using yolov5 model with different confidence threshold:
* conf_thres = 0.25: 0.4067
* conf_thres = 0.01: 0.4172
* conf_thres = 0.001: 0.4217


