# Number Plate Recognition with EasyOCR - Computer Vision Project

This repository contains a project focused on automatic number plate recognition (ANPR) using EasyOCR and Imutils. The goal of the project is to detect and recognize vehicle license plates from images, making it applicable for various tasks such as parking management, traffic monitoring, and vehicle tracking.

## Project Overview

This project leverages EasyOCR, a deep learning-based Optical Character Recognition (OCR) library, to extract text from number plates in images. Imutils is used to handle image processing tasks that facilitate accurate detection and enhance recognition accuracy. Key preprocessing techniques such as resizing, edge detection, and contour filtering are used to locate and isolate number plates before passing them to the OCR engine.

## Features

- **License Plate Detection**: Uses Imutils for image preprocessing, including edge detection and contour analysis, to accurately identify number plates.
- **Text Recognition**: Applies EasyOCR to read text from the detected license plates.
- **Versatile Applications**: Adaptable for use in traffic management, automated parking systems, and access control.

## Requirements

- **Python 3.6+**
- **EasyOCR**
- **Imutils**
- **OpenCV**

To install the required dependencies, run:
```bash
pip install easyocr imutils opencv-python
