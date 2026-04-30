# ⚾ Baseball Detection Project

This project develops an object detection pipeline using Faster R-CNN to identify baseballs in training video frames. The main goal is to detect **moving baseballs** and create tight bounding boxes around them.

## Project Overview

This repository includes two model versions:

1. **Baseline Model**  
   The original Faster R-CNN pipeline for baseball detection.

2. **Improved Model / Robustness Check**  
   An improved Faster R-CNN model focused specifically on **moving baseball detection**, with stronger preprocessing, dataset construction, evaluation, and visualization.

## Project Structure

```text
baseball-final-project/
│
├── annotations_final/                 # XML annotation files from CVAT
├── videos_final/                      # Raw baseball training videos
│
├── baseball_script.ipynb              # Baseline model notebook
├── baseball_improved_model.ipynb      # Improved Faster R-CNN robustness model
│
└── README.md                          # Project documentation

## Note:

Frames are extracted dynamically during execution and are not stored in the repository.