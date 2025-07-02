# Brain-Tumor-Segmentation
Arch Technologies Project
This project presents a hybrid deep learning approach for brain tumor detection and segmentation using two state-of-the-art models: YOLOv11 and SAM2 (Segment Anything Model 2). The system is designed to automatically identify and isolate brain tumors in medical images by combining real-time object detection with high-precision image segmentation.
YOLOv11 is used to detect the presence and approximate location of tumors through bounding boxes.

SAM2 is then applied to generate detailed pixel-level masks for the detected tumor regions.

The solution is implemented and executed entirely in Google Colab and uses a public brain tumor dataset from Kaggle. The project demonstrates how advanced models can be combined effectively to support medical diagnostics, specifically in neuro-oncology.

Key components of the project include:

Preparing and training YOLOv11 on annotated brain tumor images.

Integrating SAM2 with YOLO’s output to generate segmentation masks.

Visualizing and saving the results of detection and segmentation for further analysis.

This project reflects a meaningful step toward AI-assisted medical imaging and provides a scalable pipeline for tumor analysis in CT or MRI scans.
