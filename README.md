# Deep Learning YOLO Assignment

This repository contains my Deep Learning course assignment on YOLO object detection using a filtered 11-class subset of the MS COCO 2017 dataset.

## Student
Muhammad Saad Bin Zahid  
Roll No: 24K-8046

## Repository Contents
- `24K_8046_Yolo_Notebook.ipynb` — main Colab notebook
- `24K-8046 - Yolo Assignment.pdf` — final report
- `runs/baseline_yolov8n_gpu/` — baseline model outputs and weights
- `runs/exp_imgsz512/` — experiment model outputs and weights
- `runs/baseline_vs_experiment.png` — comparison plot
- `runs/task5_qualitative_15/` — 15 qualitative detection results

## Experiment Summary
Two YOLOv8n models were trained on the same 11-class subset of MS COCO:
- Baseline: `imgsz=320`, `epochs=5`
- Experiment: `imgsz=512`, `epochs=5`

## Final Results
### Baseline (imgsz=320)
- mAP@0.5: 0.402
- mAP@0.5:0.95: 0.2637
- Precision: 0.5227
- Recall: 0.4008

### Experiment (imgsz=512)
- mAP@0.5: 0.502
- mAP@0.5:0.95: 0.331
- Precision: 0.622
- Recall: 0.452

The 512-resolution experiment performed better and was used for the final qualitative detection results.

## Note
The full MS COCO dataset is not included in this repository because of file size. The repository contains the notebook, report, trained weights, plots, and qualitative outputs.
