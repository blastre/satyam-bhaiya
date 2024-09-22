# Sign Language Detector

**Technologies Used:** Python, YOLOv5, OpenCV, Google Colab  
**Date:** August 2024

## Overview

This project implements a real-time sign language detection system using a fine-tuned YOLOv5 model. It captures live input from a webcam and recognizes various sign language gestures.

## Features

- **Real-Time Detection:** 
  - Developed a system that uses a fine-tuned YOLOv5 model for accurate gesture recognition.
  - Integrated OpenCV for seamless handling of webcam input.

- **Custom Dataset Builder:**
  - Built and annotated a custom dataset using a Python script to ensure high-quality data for model training.
  - Captured images for specific sign language labels such as 'hello', 'thanks', 'yes', and 'no'.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/blastre/yolo-sign.git
   cd sign-language-detector
Install the required packages:

   ```bash
   pip install -r requirements.txt
Ensure you have the YOLOv5 weights file (e.g., signlang.pt) in the correct directory.


## Usage
To run the sign language detection with webcam input, use the following command:

 ```bash
   python detect.py --weights signlang.pt --source 0


## Custom Image Dataset Builder
This feature includes a Python script that automatically captures and labels images for building a custom dataset.
Images are saved in an organized directory structure, facilitating efficient dataset preparation.
## Acknowledgments
Thanks to the developers of YOLOv5 and OpenCV for their contributions to the field of computer vision.
Special thanks to any collaborators or mentors who assisted in the development of this project.
