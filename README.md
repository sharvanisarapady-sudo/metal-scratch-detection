# Metal Scratch Detection using YOLOv5

## Overview

This project detects scratches on metal surfaces using a custom-trained YOLOv5 model.

## Technologies Used

- Python
- YOLOv5
- PyTorch
- Google Colab

## Training

The model was trained on a custom dataset using YOLOv5.

Training command:
python train.py --img 640 --batch 16 --epochs 50 --data data.yaml --weights yolov5s.pt

Final trained model:
best.pt

Training notebook:
tutorial.ipynb

## Results

Sample detection outputs are available in the results folder.
