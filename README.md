# Kidney Stone Detection Using Deep Learning

**Capstone Project – North South University**

This project focuses on detecting kidney stones from medical images using deep learning techniques, specifically the YOLOv8 model. The system aims to assist in early diagnosis and improve accessibility to healthcare tools.

---

## 🔹 Project Overview

Kidney stone detection is critical for timely treatment and better patient outcomes. This project uses annotated radiological images to train a YOLOv8 model for accurate identification and localization of kidney stones.

---

## 🔹 Features

* Detects kidney stones in radiological images with high accuracy.
* Uses YOLOv8 for object detection and semantic segmentation.
* Provides visual output with bounding boxes for detected stones.
* Easy adaptation to new datasets and custom images.

---

## 🔹 Dataset

* Annotated kidney stone images sourced from **Kaggle**.
* Organized in YOLOv8 format: separate folders for training, validation, and testing images with corresponding label files.
* Random visualization of labeled data with bounding boxes for better understanding of the dataset.

---

## 🔹 Methodology

1. **Data Acquisition and Preprocessing**  
   - Dataset sourced from Kaggle in YOLOv8 format.  
   - Separate folders for training, validation, and testing images with corresponding label files.  
   - Random visualization of labeled data with bounding boxes.

2. **Development Environment**  
   - Implemented in Google Colab with GPU acceleration.  
   - Python libraries: YOLOv8, OpenCV, Pandas, Matplotlib, Seaborn.

3. **Model Training and Optimization**  
   - Fine-tuned pre-trained YOLOv8 model on the kidney stone dataset.  
   - Optimized hyperparameters: learning rate, batch size, and number of epochs.  
   - Achieved high precision and recall in stone detection.

4. **Evaluation and Visualization**  
   - Metrics: mAP, precision, recall.  
   - Visualized training progress, losses, and evaluation metrics using Matplotlib and Seaborn.  
   - Confusion matrix analysis for classification performance.

5. **Testing and Deployment**  
   - Tested on unseen data to evaluate generalization ability.  
   - Predicted kidney stones visualized with bounding boxes on images.

---

## 🔹 Project Structure

kidney-stone-detection/
└── Copy_of_KidneyStoneDetectionFinal.ipynb   <- Your notebook
└── README.md                       <- Describe what the project does and where to get the dataset

---

## 🔹 Code Snippets

- Loading and visualizing labeled training images.  
- Training YOLOv8 model.  
- Evaluating the model with precision, recall, and mAP metrics.  
- Confusion matrix generation.  
- Detecting kidney stones on custom test images.

---

## 🔹 Tools and Technologies

- **Programming:** Python  
- **Deep Learning Framework:** YOLOv8  
- **Data Processing:** OpenCV, Pandas  
- **Visualization:** Matplotlib, Seaborn  
- **Environment:** Google Colab with GPU acceleration

---








## 🔹 Authors

**Chadni Mandal**  
Bachelor in Computer Science and Engineering, North South University  

**Tanjim Subah Alam**  
Bachelor in Computer Science and Engineering, North South University  

**Sadia Hassan Chowdhury**  
Bachelor in Computer Science and Engineering, North South University  

**Ratul Dey**  
Bachelor in Computer Science and Engineering, North South University  


