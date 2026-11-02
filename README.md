<div align="center">

# 🐕 Dog Detection · YOLOv5s

**Fine-tune YOLOv5s to detect dogs in images.**

<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"> <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" alt="PyTorch"> <img src="https://img.shields.io/badge/YOLO-111F68?style=for-the-badge" alt="YOLO"> <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white" alt="Jupyter">

<a href="https://colab.research.google.com/github/KamranUmer/YoloV5s/blob/main/Object_detection_using_YOLOv5_Tutorial.ipynb"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open in Colab"></a>

</div>

<p align="center"><img src="https://github.com/KamranUmer/YoloV5s/assets/86089489/59b36998-d35d-42e8-9dec-7c22593ce7cf" alt="Dog Detection · YOLOv5s screenshot" width="85%"></p>

## 📌 Overview

Fine-tunes the small YOLOv5 model on a custom dog dataset (train/val split in YOLO format) and runs detection on new images.

## 🔬 Pipeline

- Detect, validate and train with the Ultralytics scripts
- Custom dataset: `images/` and `labels/` with train and val splits
- 20-epoch fine-tune from COCO weights

## 📊 Results

| Metric | Value |
|---|---|
| mAP@0.5 | 0.578 |
| Precision / Recall | 0.577 / 0.727 |

> Validation set: 20 images, 15 labelled dogs.

## 🚀 Getting Started

```bash
# Open the notebook in Google Colab (badge above), choose a GPU runtime,
# then run the cells from top to bottom.
```

## 🙏 Acknowledgements

- [YOLOv5](https://github.com/ultralytics/yolov5) by Ultralytics

---

<div align="center">

Built by <a href="https://github.com/KamranUmer"><b>Kamran Umer</b></a> · ⭐ Star the repo if you find it useful

</div>
