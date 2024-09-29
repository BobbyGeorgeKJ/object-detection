# Object detection using deep learning with OpenCV and Python

The OpenCV dnn module now facilitates inference execution on pre-trained deep learning models from prominent frameworks such as Caffe, Torch, and TensorFlow.

In the realm of object detection, leading frameworks include:

YOLO
SSD
Faster R-CNN
Recently, the OpenCV dnn module has expanded its capabilities by incorporating support for YOLO/DarkNet models, enhancing its versatility for object detection tasks.

## Dependencies

- opencv
- numpy

# To install use the following code on your terminal

`pip3 install numpy opencv-python`

**Note: Compatability with Python 2.x is not officially tested.**

## YOLO (You Only Look Once)

- Download the pre-trained YOLO v3 weights file from this [link](https://pjreddie.com/media/files/yolov3.weights)
- Place it in the current directory
- Provided all the files are in the current directory
- The below command will apply object detection on the input image `road.jpg`.
  `python3 yolo_opencv.py --image road.jpg --config yolov3.cfg --weights yolov3.weights --classes yolov3.txt`
