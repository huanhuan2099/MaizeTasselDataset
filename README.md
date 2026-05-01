# MaizeTassel-Dataset
MaizeTassel: A UAV-based dataset for maize tassel detection in complex field environments. We will provide the download link after the paper is accepted.

## Overview

MaizeTassel is a UAV-based dataset for maize tassel detection in complex agricultural field environments. 
It is designed to support research in fine-grained object detection, high-density target localization, and precision agriculture applications.

The dataset is collected from real maize fields under diverse conditions, including variations in illumination, occlusion, viewpoint, and background complexity.

---

## 📊 Dataset Statistics

- Total images: **3,794**
- Image resolution: **1024 × 1024**
- Total annotations: **75,273 maize tassels**
- Average objects per image: **19.8**
- Maximum objects per image: **130**

---

## 🌾 Data Collection

The dataset was collected using a **DJI Mini 4 Pro UAV** in agricultural fields located in:

- Wuhan, Hubei Province, China  
- Shangqiu, Henan Province, China  

All images were captured under natural lighting conditions with varying:

- Flight altitudes  
- Viewing angles  
- Illumination conditions  
- Occlusion levels  

---

## 🧩 Dataset Splits

| Split | Images | Ratio |
|------|--------|------|
| Train | 2,218 | 58% |
| Val   | 756   | 20% |
| Test  | 820   | 22% |

---

## 📦 Annotation Format(YOLO)

Each label file corresponds to an image and follows YOLO format:
<class_id> <x_center> <y_center> <width> <height>

All coordinates are normalized to [0, 1].

Only one class is defined:
0: tassel

---

## 📜 License

This dataset is released for academic research only. Commercial use is not allowed without permission.

---

## 📚 Citation

If you use this dataset, please cite:
