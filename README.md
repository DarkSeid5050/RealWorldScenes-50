# RealWorldScenes-50

**RealWorldScenes-50** is a custom dataset of **50 real-world images** annotated with bounding boxes for five object categories.  
The dataset contains a mix of urban, natural, and everyday scenes, making it suitable for small-scale experiments in object detection.

## 📌 Classes
1. **Person**
2. **Food**
3. **Vehicle**
4. **Animal**
5. **Electronic Device**


## 📂 Dataset Structure

RealWorldScenes-50/
│── data/
│ ├── images/ # 50 raw images
│ ├── labels/ # YOLO 1.1 format (.txt files)
│ └── annotations/ # COCO 1.0 format (.json file)
│── guidelines/
│ └── annotation_guidelines.md
│── assets/
│ └── sample_screenshots/
│── README.md



## 🛠 Tools Used
- **Annotation Tool:** [CVAT](https://cvat.ai)  
- **Export Formats:** YOLO 1.1, COCO 1.0  
- **Labeling Technique:** Manual bounding box annotations

## 📷 Sample Annotation
![Annotation Example](assets/sample_screenshots/example1.jpg)

## 📜 License
This dataset is intended for **educational and portfolio purposes only** and is not for commercial use.
