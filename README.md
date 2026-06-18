
# Sewer Defect Detection and Severity Analysis using YOLOv8

## Overview

This project presents a deep learning-based framework for automatic sewer pipeline defect detection using YOLOv8m and rule-based severity analysis.

## Defect Classes

- Buckling
- Crack
- Debris
- Hole
- Joint Offset
- Obstacle
- Utility Intrusion

## Dataset

Sewer Defects v1i Dataset

~800 CCTV inspection images

2364 annotated defect instances

7 defect categories

## Model

YOLOv8m

Input Size: 640×640

Optimizer: SGD

Epochs: 120–150

## Results

Precision: 55.8%

Recall: 46.7%

mAP@0.5: 45.7%

mAP@0.5:0.95: 19.7%

## Severity Analysis

A geometry-aware severity estimation module classifies defects into:

- Minor
- Moderate
- Severe

using bounding-box area, aspect ratio, and defect-specific engineering rules.

## Paper

IEEE-format research paper included.
