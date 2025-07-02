# Brain-Tumor-Segmentation
## Arch Technologies Project

This project focuses on the implementation of a deep learning-based solution for automated brain tumor detection and segmentation using a two-stage pipeline that combines the strengths of YOLOv11 (You Only Look Once) for object detection and SAM2 (Segment Anything Model 2) for semantic segmentation. The goal of the project is to accurately detect tumor regions in medical images and generate precise, pixel-level segmentations that can support radiologists and researchers in neuro-oncology. Early and accurate tumor detection is critical in clinical practice, and this project explores how modern AI tools can assist in medical diagnostics with speed, precision, and reproducibility.

🔍 Key Features

- YOLOv11 is leveraged for its real-time object detection capability, allowing the model to identify tumor locations within MRI scans via bounding boxes. YOLOv11 is known for its high speed and accuracy, making it suitable for medical imaging workflows that require both performance and precision.-

- SAM2, developed by Meta AI, is used to perform instance segmentation by generating detailed masks around the tumor regions identified by YOLO. SAM2 enables the model to go beyond coarse detection and accurately delineate the boundaries of the tumor.

- The project was developed entirely in Google Colab to ensure ease of access and reproducibility. It also integrates PyTorch, OpenCV, and Matplotlib for model training, image processing, and result visualization.

- A Kaggle-sourced dataset containing labeled brain tumor images was used for training and validation. The dataset was formatted to meet the requirements of YOLO, with annotations provided in standard YOLO format.

- The final pipeline is capable of taking unseen MRI brain scan images and outputting both:

1. Tumor classification and bounding box detection.

2. High-resolution segmentation masks that isolate the tumor area from surrounding tissue.
