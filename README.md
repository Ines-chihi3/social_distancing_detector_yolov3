# social_distancing_detector_yolov3

## introduction :

The only way to prevent the spread of COVID-19 is Social Distancing. Keeping a safe distance from each other is the ultimate way to prevent the spread of this disease

in this project we detect where each person is in real-time, return a bounding box that turns red if the distance between two people is dangerously close. This can be used by governments to analyze the movement of people and alert them if the situation turns serious.

## Requirements

* Python
* Numpy
* OpenCV
* Scipy
* Yolov3 : Object Detection models


## project pipeline discription :

![image](https://github.com/Ines-chihi3/social_distancing_detector_yolov3/blob/master/pipeline.PNG)

## results :
https://github.com/Ines-chihi3/social_distancing_detector_yolov3/blob/df78803de2747e6fda8fdbaacb85d3ebc140442a/test_video/pedestrians_output.avi
## conclusion and improvement : 

this project is only a proof of concept and was not made to be use to monitor social distancing in public or private areas because of ethical and privacy issues.
I am well aware that this project is not perfect so these are a few ideas how this application be improved :
* Using a faster model in order to perform real-time social distancing analysis.
* Automatic calibration is a very well known problem in Computer vision and could improve a lot the bird eye view transformation on different scenes.

## sources :

* https://www.analyticsvidhya.com/blog/2020/05/social-distancing-detection-tool-deep-learning/
* https://www.pyimagesearch.com/2020/06/01/opencv-social-distancing-detector/
