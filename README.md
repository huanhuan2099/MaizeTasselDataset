# MaizeTassel-Dataset
MaizeTassel: A UAV-based dataset for maize tassel detection in complex field environments

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

## 📦 Annotation Format

We provide annotations in **COCO format**.

Each image is labeled with bounding boxes for maize tassels:

```json
{
  "bbox": [x, y, width, height],
  "category_id": 1
}
