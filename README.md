# Image_Quality_Blur_Detection

This is an image classification project that predicts whether an image is **blurry**, **original**, or **sharp**.  
It was created following a tutorial on Dataquest and with guidance from ChatGPT.  

---

##  Project Overview

This project demonstrates a complete **machine learning pipeline**, from dataset preparation to model training, evaluation, and visualization.  

Key highlights:  
- End-to-end image classification workflow  
- Automated preprocessing: generating sharp and blurry images  
- CNN model using TensorFlow/Keras  
- Evaluation and visualization of predictions  
- Portfolio-ready example for AI/ML internships  

---

## 📁 Dataset

- **Base dataset:** CIFAR-10 images  
- **Number of images used:** 500  
- **Processed into three categories:**  
  1. **Original** – unmodified CIFAR images  
  2. **Sharp** – identical copies of original images  
  3. **Blurry** – Gaussian-blurred versions of sharp images  

All images are stored in the `dataset/` folder, ready for loading into TensorFlow.

---

## 🗂 Project Structure

Image_Quality_Blur_Detection/
├── dataset/
│ ├── original/ # Original CIFAR images
│ ├── sharp/ # Sharp copies
│ └── blurry/ # Gaussian-blurred images
├── models/ # Saved trained models
├── results/ # Accuracy plots and prediction results
└── Image_Quality_Blur_Classification.ipynb # Main notebook

## Key Steps

Mount Google Drive and set up project folders.
Load CIFAR-10 images and select first 500 images.
Save images as JPEGs in the original/ folder.
Create sharp copies in the sharp/ folder.
Generate blurry images using Gaussian blur in the blurry/ folder.
Load images into TensorFlow with image_dataset_from_directory.
Build, compile, and train a CNN model, including data augmentation and Dropout layers.
Evaluate model performance and visualize predictions.

## Results

The trained CNN can classify images as blurry, original, or sharp.
Sample predictions and misclassifications are visualized in the notebook.
Training and validation accuracy over epochs are plotted for performance analysis.

## How to Run

Open Image_Quality_Blur_Classification.ipynb in Google Colab.
Mount Google Drive for dataset and result storage.
Run all cells sequentially.
View results and plots in the notebook or in the results/ folder.

## Portfolio Highlights

Automated image preprocessing pipeline for blur/sharp generation.
CNN model with data augmentation and Dropout layers to prevent overfitting.
Full analysis of predictions, including visualization of misclassifications.
Well-documented, reproducible notebook ready for internship demonstration.

## Requirements/Dependencies
- Python 3.8+  
- TensorFlow  
- OpenCV (`cv2`)  
- NumPy  
- Pandas  
- Matplotlib  
- Pillow  

