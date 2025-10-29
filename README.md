# Real-time Color Detection using OpenCV and Python

Real-time color detection demo that detects red objects from a live camera feed using OpenCV. The script converts each frame to HSV for robust color segmentation, applies morphological filtering to reduce noise, finds object contours, draws bounding rectangles, and displays the detected average RGB color on the video.

## Features
- Real-time detection of red-colored objects.
- HSV-based color segmentation (more robust than RGB).
- Morphological operations to remove noise.
- Bounding boxes and average RGB label for each detected object.
- Simple to tweak HSV ranges and noise-filter parameters.

## Requirements
- Windows (tested)
- Python 3.7+
- Libraries:
  - opencv-python
  - numpy

Install dependencies:
````bash
pip install opencv-python numpy