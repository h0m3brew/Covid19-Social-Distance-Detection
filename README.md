# Social-Distancing-Analyser-wrt.-COVID-19
An AI tool to prevent spreading of coronavirus (COVID-19) by using computer vision on video surveillance.

## For education purpose only

Social Distancing Analyser automatically detects the extent to which social distancing protocols are followed in the area.
Deploying it on current surveillance systems and drones used by police to monitor large areas can help to prevent coronavirus by allowing automated and better tracking of activities happening in the area. It shows analytics of the area in real time. It can also be used to alert police in case of considerable violation of social distancing protocols in a particular area.

#### Result:

## Features:
* Get the real time analytics such as:
   - Number of people in a particular area
   - Number of people in high risk
   - The extent of risk to a particular person.

## Things needed to be improved :
* Auto-calibration [For the given sample video, I've calibrated the model by simulating a 3D depth factor based on the camera position and orientation.
* Faster processing

## Installation:
* Fork the repository and download the code.
* Download the following files and place it in the same directory
   - https://github.com/pjreddie/darknet/blob/master/cfg/yolov3.cfg
   - https://pjreddie.com/media/files/yolov3.weights
* For slower CPUs, use yolov3-tiny (link in the code comments)
* Install all the dependenices
* Run social_distancing_analyser.py