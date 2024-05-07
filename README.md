# Real Time Object Detection
This repository contains a Python implementation of real-time object detection using the SSD MobileNet model integrated with OpenCV. The code allows for object detection using either a webcam or a custom video file. This project is ideal for educational purposes, hobbyist applications, or as a starting point for more complex object detection systems.

# Project Structure
 - model_data/: Folder containing the SSD MobileNet model files and class names.
 - ssd_mobilenet_v3_large_coco_2020_01_14.pbtxt: Configuration file for the model.
 - frozen_inference_graph.pb: Pre-trained model weights.
 - coco.names: List of object classes that the model can detect.
 - detector.py: Main Python script that performs object detection.
# Requirements
This project uses Python 3.x and the following packages:
 - OpenCV
 - NumPy

To install the required packages, run:

 - pip install opencv-python numpy
 - pip install opencv-python


# Usage
## 1.Clone the Repository
git clone https://github.com/hxbeeb11/Real-Time-Object-Detection.git

## 2.Run the Detector
### To detect objects in a video file:

python detector.py --videoPath= "path_to_your_video.mp4"

### To detect objects using a webcam:
python detector.py --videoPath= 0
# Configuration
You can modify the detector.py script to change the detection configuration such as confidence thresholds and input video path.

# Contributing
Contributions to this project are welcome. Please consider the following ways to contribute:
 - Reporting bugs
 - Suggesting enhancements
 - Submitting pull requests with improvements
