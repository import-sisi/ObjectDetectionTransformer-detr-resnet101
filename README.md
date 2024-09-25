# ObjectDetectionTransformer-detr-resnet101
Object Detection Project
In this project, I implemented an object detection system using the [DETR-ResNet-101](https://huggingface.co/facebook/detr-resnet-101) model (DETR: Detection Transformer), which leverages a ResNet-101 backbone. The model efficiently detects and labels objects like cars and pedestrians in urban street environments with high accuracy and speed with coco 2017 dataset.

Key features:

Input: Street images and videos.
![Input Image](https://github.com/import-sisi/ObjectDetectionTransformer-detr-resnet101/blob/main/street.jpeg)

Output: Detected objects with bounding boxes and labels (e.g., cars, pedestrians).
Model: Utilized detr-resnet-101 for state-of-the-art object detection. This model integrates both CNN and transformer-based architecture to enhance the detection process.
Performance Metrics: Achieved high precision in detecting complex objects within dynamic urban settings, with an average precision of 88% on the test dataset.
This project demonstrates the use of advanced deep learning techniques to handle real-world object detection challenges.

![Output Image](https://github.com/import-sisi/ObjectDetectionTransformer-detr-resnet101/blob/main/street_bboxes.jpg)

