# landslide-detection-ml
# Landslide Detection using YOLOv8 and U-Net

## Overview
This project implements landslide detection and segmentation using deep learning models on Sentinel-1, Sentinel-2, and DEM satellite data.

## Models Used
- YOLOv8s for object detection
- U-Net for semantic segmentation

## Dataset
Multi-sensor remote sensing data including SAR (Sentinel-1), multispectral imagery (Sentinel-2), and elevation data (DEM).

## Workflow
- Data preprocessing and mask/label preparation  
- Training YOLOv8s for landslide detection  
- Training U-Net for pixel-level segmentation  
- Model evaluation and comparison

## Results
- Evaluation using Precision, Recall, F1-score, mAP (YOLO)  
- IoU used for segmentation performance  
- Visual results included in `/results/images`
- U-net performed significantly better

## Key Insight
Compared detection-based vs segmentation-based approaches for improved landslide mapping accuracy.

## Note
This repository contains experimental implementations for academic and research purposes.
