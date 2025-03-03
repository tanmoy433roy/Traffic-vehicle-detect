
# VEHICLE DETECTION

This project implements real-time vehicle detection and tracking using YOLOv4 and OpenCV's deep learning module (cv2.dnn). It detects vehicles in a video stream and tracks them across frames by assigning unique IDs to each detected vehicle.




## Features

- Object Detection: Uses YOLOv4 to detect vehicles in video frames.

- Tracking Mechanism: Tracks detected objects using Euclidean distance and assigns IDs to them.

- Customizable Parameters: Thresholds for confidence and non-max suppression can be modified.

- Supports Any Video Input: Works with any video file.


## Deployment

Install the necessary dependencies:

```bash 
pip install opencv-python nump
```

## Project Structure
- `vehicle-detection/`
  - `dnn_model/`
    - `yolov4.weights`
    - `yolov4.cfg`
    - `classes.txt`
  - `object_detect.py`
  - `vehicle_tracking.py`
  - `video3.mp4` (Replace with your own video)

## Roadmap

1. Clone the Repository

2. Download YOLOv4 Weights
Download the yolov4.weights file from the official YOLO website and place it in the dnn_model/ directory.

3. Run the Vehicle Detection and Tracking Script
``` python
object_detect.py
object_track.py
```
4. Using a Different Video
Replace video3.mp4 in vehicle_tracking.py with your desired video file:

```python
cap = cv2.VideoCapture("your_video.mp4")
```

