# Number Plate Detection using Yolov8

## Description

This project utilizes the Roboflow API and a trained Yolov8 model to detect number plates from various regions around the world. After detection, OpenCV (cv2) is used for image classification and cropping, followed by text extraction using the EasyOCR library.

## Libraries

- roboflow
- cv2 (OpenCV)
- matplotlib (pyplot)
- easyocr
- matplotlib.image (mpimg)

## Installation

To run this project on your machine or in any environment, you need to install the required libraries using the following commands:

```bash
!pip install roboflow
!pip install easyocr
```
## Usage
This number plate recognition system has the following uses and benefits:

- Detects number plates from various regions worldwide.
- Utilizes the Roboflow API for seamless integration.
- Employs Yolov8 for accurate object detection.
- Uses OpenCV for image classification and cropping.
- Extracts text from number plates using EasyOCR.
- Provides a versatile and robust solution for automating number plate-related tasks.
