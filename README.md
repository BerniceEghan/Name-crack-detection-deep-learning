# Crack Detection using Deep Learning

## Overview
This project implements and compares Mask R-CNN and YOLO for crack detection and segmentation.

## Models
- Mask R-CNN (ResNet-50 + FPN)
- YOLO Segmentation Model

## Results

| Model | Detection (mAP@50) | Segmentation (mAP@50) |
|------|-------------------|-----------------------|
| Mask R-CNN | ~0.64 | ~0.10–0.18 |
| YOLO | ~0.85 | ~0.57 |

## Key Findings
- YOLO performs better overall
- Crack segmentation is challenging due to thin structures

## Project Structure
- notebooks → training notebooks
- models → trained weights
- results → outputs and plots
- report → final report

## Installation
pip install -r requirements.txt
