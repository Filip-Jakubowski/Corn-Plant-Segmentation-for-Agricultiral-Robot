Corn Plant Detection and Tracking with YOLOv8

This project investigates the use of deep learning for real-time instance segmentation and tracking of corn and weed plants in agricultural fields. It was conducted at Poznan University of Technology as part of research in precision agriculture and agricultural robotics.

Overview

The system leverages the YOLOv8-seg model to detect, segment, and track individual corn and weed instances from a fixed-angle camera mounted on a moving platform. This approach aims to enable automated weed control, precision farming, and efficient resource allocation in agricultural settings.

Features

- Real-time instance segmentation using YOLOv8-seg

- Integration with a ROS2 camera pipeline

- Dataset creation and annotation using Labelbox and Roboflow

- Data augmentation and preprocessing

- Built-in multiple object tracking (MOT) via YOLOv8

- Evaluation using precision, recall, confusion matrix, and loss curves

System Architecture

1. Data Acquisition: 102 annotated images and video streams collected at a fixed 40° camera angle.

2. Annotation: Semantic and instance segmentation with Roboflow.

3. Model Training: YOLOv8-seg fine-tuned for plant and weed detection.

4. Tracking: Real-time MOT based on YOLOv8’s built-in tracker.

5. Deployment: Model integrated into ROS2 nodes for live inference.

Tech Stack

-Python, OpenCV, Ultralytics YOLOv8

-Roboflow, Labelbox

-ROS2

-TensorBoard for training visualization

Limitations

-Fixed camera angle affects segmentation accuracy.

-Evaluation performed under controlled environmental conditions.

-Model trained on a small dataset (~100 annotated images).



Contributors

-Filip Jakubowski

-Michał Remigiusz Janiszewski

-Ignacy Laurenty Kajdan

-Kuba Grzesiecki

-Michał Sikorski

Supervisor: MSc. Iman Esfandiyar
