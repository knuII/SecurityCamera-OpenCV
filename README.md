# SecurityCamera-OpenCV

This is a simple security camera application created using OpenCV. It detects faces and bodies in the camera feed and records video when a detection is made.

## Features

- Real-time face and body detection.
- Video recording when a face or body is detected.
- Automatic video file naming with timestamps.
- Easy-to-use interface.

## Requirements

- Python 3.x
- OpenCV (cv2)
- NumPy

## Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/your-username/SecurityCamera-OpenCV.git
2. Install the required libraries
   ```bash
   pip install opencv-python numpy

## Usage
Start the application, and it will open a window showing the camera feed.
The application will automatically start recording when it detects a face or body.
Recorded videos will be saved in the current directory with timestamps.

## Configuration
You can configure the application by modifying the following constants in security_camera.py:

SECONDS_TO_RECORD_AFTER_DETECTION: Adjust the time to continue recording after detection.
VIDEO_SAVE_DIRECTORY: Change the directory where recorded videos are saved.
