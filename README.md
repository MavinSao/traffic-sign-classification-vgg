# Traffic Sign Classifier

## Project Overview
This project aims to develop a Traffic Sign Classifier to recognize various traffic sign categories using a labeled dataset of images. The project incorporates a comparative study of fine-tuning strategies for the classification model by exploring the performance difference between two approaches:
1. Freezing all layers except the last 5 layers.
2. Freezing all layers except the last 10 layers.

The goal is to identify the optimal fine-tuning strategy that yields the highest classification accuracy while balancing computational efficiency.

## Dataset

kaggle: https://www.kaggle.com/datasets/ahemateja19bec1025/traffic-sign-dataset-classification

The dataset contains traffic sign images categorized into multiple classes. Each class corresponds to a specific traffic sign, and the dataset is organized as follows:
- **Images**: Stored in folders, where each folder represents a class labeled by its unique ID.
- **Labels**: A `labels.csv` file maps each class ID to its corresponding traffic sign name.

Example classes include:
- Speed limit (5km/h)
- Speed limit (40km/h)
- No entry
- Zebra Crossing

Each class folder contains several images representing the respective traffic sign. The dataset structure ensures compatibility with machine learning workflows for training and evaluation.
