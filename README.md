# YOLOv5 & YOLOv8 Object Detection Evaluation  

This project evaluates and compares **YOLOv5** and **YOLOv8** object detection models using the **COCO128 dataset**.  
It demonstrates how to run inference, compute evaluation metrics, and visualize predictions against ground truth annotations.  

---

## ✨ Features
- Load **pretrained YOLOv5s** and **YOLOv8s** models.  
- Perform **object detection** on COCO128 images.  
- Compute evaluation metrics:  
  - **Intersection over Union (IoU)**  
  - **Precision**  
  - **Recall**  
  - **F1-Score**  
  - **Accuracy**  
- Visualize detection results:  
  - **Blue box** → Ground Truth  
  - **Green box** → Prediction  

---

## 📂 Dataset
- **COCO128**: a lightweight version of the COCO dataset for fast experimentation.  
- Images and YOLO-format annotations are automatically downloaded.  

---

## 📊 Results

- After running the evaluation, the following metrics are displayed:

- **YOLOv8 (sample results)**:

- Precision: ~0.82

- Recall: ~0.78

- F1-Score: ~0.80

- Accuracy: ~0.79

- Average IoU: ~0.65

- **YOLOv5 (sample results)**:

- Precision: ~0.79

- Recall: ~0.75

- F1-Score: ~0.77

- Accuracy: ~0.76

- Average IoU: ~0.62
