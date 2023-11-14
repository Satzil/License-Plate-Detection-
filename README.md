# License Plate Detection using OpenCV, YOLOv5, and EasyOCR

## Overview

This project aims to implement a license plate detection system using computer vision techniques. The project leverages the power of OpenCV for image processing, YOLOv5 for object detection, and EasyOCR for optical character recognition.

-  **OpenCV:** OpenCV (Open Source Computer Vision Library) is utilized for image processing tasks. It provides a rich set of tools and functions for working with images and videos.

-  **YOLOv5:** YOLO (You Only Look Once) is a real-time object detection system. YOLOv5, an upgraded version, is employed in this project for its speed and accuracy in detecting objects, including license plates.

-  **EasyOCR:** EasyOCR is a simple and efficient optical character recognition (OCR) library. It is used to extract text information from the detected license plates.


## Project Workflow

1.  **Image Input:** The system takes input images containing vehicles with license plates.

2.  **Object Detection with YOLOv5:** YOLOv5 is employed to detect the presence and location of license plates in the input images. This step involves real-time object detection.

3.  **Image Processing with OpenCV:** OpenCV is used for additional image processing tasks, such as resizing, cropping, and enhancing the regions containing license plates.

4.  **Optical Character Recognition with EasyOCR:** The cropped license plate regions are processed using EasyOCR to extract the alphanumeric characters present on the plates.

5.  **Output and Visualization:** The final output includes the original image with bounding boxes around detected license plates and the extracted text from those plates.
