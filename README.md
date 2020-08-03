# face-detection
This is a python code for detecting faces from a video stream from webcam and capture photos when there is a large diversion or movement in the face using OpenCV

commandline argument for execting the python file
python detect_faces_video.py --prototxt deploy.prototxt.txt --model res10_300x300_ssd_iter_140000.caffemodel

## Description of all the files in this repository
### Prototext file
A prototext file basically contains the structure or protocols of the model,
here we are using a caffemodel so we have the respective prototext file
### res10_300x300_ssd_iter_140000.caffemodel file
This contains the pre trained model that is used to detect faces built using caffe framework
### detect_faces_video.py file
This file contains the python code for boxing the face in the video streaming and saving captured photes
