# Kidney Stone Detection Using Deep Learning
**Capstone Project – North South University**

---

## Overview
This project focuses on detecting kidney stones from medical images using deep learning, specifically the YOLOv8 model. The system aims to assist in early diagnosis and improve accessibility to healthcare tools by automatically identifying and localizing kidney stones.

---

## Motivation
Working on this project sparked my interest in **bioinformatics and computational biology**, demonstrating how computational algorithms can transform complex medical data into actionable insights for healthcare applications.

---

## Features
- Detects kidney stones in radiological images with high accuracy.
- Uses YOLOv8 for object detection and semantic segmentation.
- Provides visual output with bounding boxes for detected stones.
- Adaptable to new datasets and custom images.

---

## Dataset
- Annotated kidney stone images sourced from Kaggle.
- Organized in YOLOv8 format: separate folders for training, validation, and testing images with corresponding label files.
- Random visualization of labeled data for quality checking.

---

## Methodology

### Data Acquisition & Preprocessing
- Loaded and visualized labeled images to ensure dataset quality.
- Split data into training, validation, and testing sets.

### Model Training & Optimization
- Fine-tuned a pre-trained YOLOv8 model on the kidney stone dataset.
- Optimized hyperparameters: learning rate, batch size, and epochs.
- Achieved high precision and recall for stone detection.

### Evaluation & Visualization
- Metrics: **mAP**, precision, recall.
- Visualized training progress, losses, and evaluation metrics using Matplotlib and Seaborn.
- Performed confusion matrix analysis for classification performance.

### Testing & Deployment
- Evaluated model on unseen images to verify generalization.
- Visualized predicted kidney stones with bounding boxes.

---

## Results
- Achieved **mAP: XX%**, **Precision: YY%**, **Recall: ZZ%** on the test set.
- Demonstrated effective automated detection with potential for clinical decision support.

---

## Tools & Technologies
- **Programming:** Python
- **Deep Learning Framework:** YOLOv8
- **Data Processing:** OpenCV, Pandas
- **Visualization:** Matplotlib, Seaborn
- **Environment:** Google Colab with GPU acceleration

---

## Usage / Code Snippets
```python
# Load and visualize labeled training images
from utils import visualize_dataset
visualize_dataset(train_images_path, train_labels_path)

# Train YOLOv8 model
from ultralytics import YOLO
model = YOLO('yolov8n.pt')
model.train(data='kidney_stone.yaml', epochs=50, batch=16)

# Evaluate model
metrics = model.val()
print(metrics)

# Detect kidney stones on custom image
results = model.predict('test_image.jpg')
results.show()
```
---







## Authors

**Chadni Mandal**  
Bachelor in Computer Science and Engineering, North South University  

**Tanjim Subah Alam**  
Bachelor in Computer Science and Engineering, North South University  

**Sadia Hassan Chowdhury**  
Bachelor in Computer Science and Engineering, North South University  

**Ratul Dey**  
Bachelor in Computer Science and Engineering, North South University  


