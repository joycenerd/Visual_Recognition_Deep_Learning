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

[[report](https://github.com/joycenerd/yolov5-svhn-detection/blob/main/docs/REPORT.pdf)] [[code](https://github.com/joycenerd/yolov5-svhn-detection)]

## Nuclei Segmentation
We participate in nuclei segmentation challenge on CodaLab. In this challenge, we perform instance segmentation on TCGA nuclei dataset from the 2018 Kaggle Data Science Bowl. This dataset contains 24 training images with 14,598 nuclei and 6 test images with 2,360 nuclei. We apply four existing methods to solve this challenge.

Testing mask mAP:
* Mask RCNN: 0.2323
* Cascade Mask RCNN: 0.2444
* PointRend: 0.2439
* Mask Scoring RCNN: 0.2420

[[report](https://github.com/joycenerd/mmdet-nucleus-instance-segmentation/blob/main/docs/REPORT.pdf)] [[code](https://github.com/joycenerd/mmdet-nucleus-instance-segmentation)]

## Image Super Resolution
We participate in super resolution challenge on CodaLab. In this challenge, we perform image super resolution on the dataset provided by the TA. There are 291 high-resolution images in the training set. There are 14 low-resolution images, which is generated by performing bicubic and shrinking the original image by 1/3 in the testing set. We apply super-resolution feedback network (SRFBN) to solve this task.

Testing PSNR (dB)
- SRFBN-S: 28.1438
- SRFBN-L: 29.3645

[[repor](https://github.com/joycenerd/image-super-resolution/blob/main/docs/REPORT.pdf)] [[code](https://github.com/joycenerd/image-super-resolution)]


