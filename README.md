# Computer Vision and Deep Learning

This repository contains a collection of Jupyter notebooks showcasing various computer vision tasks and applications using Python. Each notebook is designed to provide insights into different aspects of computer vision or deep learning, ranging from fundamental operations to advanced techniques.

## Notebooks

1. **cv-basics:**
   - Fundamental computer vision operations using the OpenCV library.
   - Covers image loading, translation, rotation, shearing, and scaling operations.
   - Visualizations at each step for better understanding.

2. **image-stitching-segmentation:**
   - Demonstrates advanced computer vision techniques.
   - First section focuses on image stitching using OpenCV's Stitcher module.
   - Second part delves into image segmentation using Canny edge detection and contour drawing.

3. **object-detection/color-detection:**
   - Focuses on color detection in an image using OpenCV.
   - Utilizes the HSV color space for accurate color segmentation.
   - Identifies contours in the segmented image and outlines them for visualization.

4. **object-detection/hand-detection:**
   - Utilizes the MediaPipe library to detect hands in a live video feed.
   - Distinguishes between left and right hands and displays real-time labels.
   - Continuously runs until the user presses 'q' to exit.

5. **object-detection/number-plate-detection:**
   - Focuses on identifying a number plate in a given image.
   - Employs image preprocessing techniques such as grayscale conversion and edge detection.
   - Uses contour analysis to identify and outline the potential number plate region.

6. **mammooty-mohanlal-classifier:**
   - Implements a Convolutional Neural Network (CNN) for binary image classification.
   - Classifies images of Indian actors Mammooty and Mohanlal.
   - Dataset taken from [Dataset Link](https://www.kaggle.com/datasets/arjunachu/mamooty-mohanlal)
   - Provides notebooks using pretrained models like InceptionV3, VGG16, VGG19, and ResNet.

## Usage
Feel free to explore each notebook for visualizations and practical implementations.

## Acknowledgments
The notebooks in this repository are created with the intent of promoting learning and understanding in the domain of computer vision and deep learning. Contributions and feedback are welcome.