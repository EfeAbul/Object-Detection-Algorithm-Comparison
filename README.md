# Object-Detection-Algorithm-Comparison

This repository presents a comparative study of different object detection algorithms applied to a limited custom dataset. The aim is to evaluate the performance, accuracy, and practical usability of popular object detection models.

# Project Overview
The project includes implementation and evaluation of the following object detection algorithms:

- YOLOv8
- Faster R-CNN
- SSD (Single Shot MultiBox Detector)

Each model is trained and tested using the same dataset and evaluation metrics to ensure a fair comparison.

# Repository Structure
```
Object-Detection-Algorithm-Comparison/
├── yolov8/              # YOLOv8 training and evaluation scripts
├── faster_rcnn/         # Faster R-CNN implementation and results
├── ssd/                 # SSD implementation and results
├── results/             # Evaluation results and visual comparisons
└── README.md            # Project documentation
```

# Evaluation Metrics

- Precision & Recall
- Confusion Matrix
- Per-Class Accuracy
- Inference Speed

Visual results and metric comparisons are available in the `results/` directory.

# Dataset

The dataset used in this project includes various vehicle classes such as cars, trucks, buses, ambulances, and motorcycles. 

**Note**: The dataset is limited in size and scope, which may affect the generalization capability of the trained models. Therefore, the results should be interpreted within this constraint.

Download Dataset [(Google Drive)](https://drive.google.com/file/d/1tWEiju-FyDP79QaWj1TsLFSNc4QHoeRa/view?usp=sharing)

Place the dataset under a common `data/` folder or as required by each model.

# Goal

The goal is to help researchers and practitioners quickly understand how different object detection models perform under similar conditions using a constrained dataset, and to choose the most suitable model for their applications.
