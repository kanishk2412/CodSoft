Suspicious Activity Detection in Crowded Areas

This project aims to detect suspicious activities in crowded environments using a combination of YOLOv5 for object detection and motion analysis. The focus is on detecting behaviors like sudden movements or running, which might indicate suspicious activities. The solution is implemented in Python using Google Colab.

Overview

The project utilizes a pre-trained YOLOv5 model to detect people in a video feed. Using centroid tracking, the movement of individuals is monitored to identify sudden or unusual movements, which are flagged as suspicious activities. The system outputs an annotated video with bounding boxes and alerts for detected suspicious activities.

Features

Person Detection: Uses YOLOv5 to detect people in the video frames.

Suspicious Activity Identification: Monitors movement across frames to detect running or sudden movements.

Annotation: Bounding boxes for detected people and alerts for suspicious activities.

Real-time Analysis: Analyzes video frames in real-time to provide immediate feedback.

Technologies Used

YOLOv5: Object detection for identifying people.

OpenCV: Video processing and drawing bounding boxes.

Google Colab: Environment used for training and inference.

PyTorch: Deep learning framework for running the YOLOv5 model.

Installation

Clone the YOLOv5 repository:

Install the requirements:

Dataset Preparation

Extract Frames from video files to create training and validation datasets.

Annotate the Frames using a tool like LabelImg to generate bounding boxes for people in the frames.
