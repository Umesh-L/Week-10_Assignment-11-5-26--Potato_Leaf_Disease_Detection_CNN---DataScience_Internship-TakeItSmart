# Potato Leaf Disease Detection using Image Classification 🌿🤖

This repository contains the **Week-10 assignment** for the **Data Science Internship at Take It Smart** 🎓.

## Project Overview 🔍

This project solves a multi-class image classification problem using a CNN model to identify potato leaf diseases from images. The notebook classifies leaves into three categories:

1. Early Blight
2. Late Blight
3. Healthy

The workflow covered in the notebook includes:

1. Dataset download and inspection
2. Data understanding with sample image visualization
3. Image preprocessing and augmentation
4. CNN model building
5. Model training and validation
6. Performance evaluation using accuracy, loss, confusion matrix, and classification report
7. Final insights and interpretation

## Repository Structure 🗂️

```text
Week-10 Assignment__11-4-26/
├── Potato_Leaf_Disease_Detection_using_Image_Classification.ipynb
├── Potato_Leaf_Disease_Detection_using_Image_Classification.ipynb - Colab notebook.pdf
├── Task pdf/
│   └── Task4_CNN.pdf
├── Output snapshots/
│   ├── sample image from each class.png
│   ├── CNN  model architecture summary.png
│   ├── Model accuracy and Model loss graphs.png
│   ├── Confusion matrix heatmap.png
│   └── Classificaiton report.png
└── README.md
```

## Dataset 🧾

- **Source:** Kaggle dataset downloaded with `kagglehub`
- **Dataset used:** `hafiznouman786/potato-plant-diseases-data`
- **Domain:** Potato leaf disease classification
- **Target Classes:** Early Blight, Late Blight, Healthy

The notebook loads the dataset from the PlantVillage directory structure and visualizes sample images before training.

## Notebook 📓

- **Main notebook:** `Potato_Leaf_Disease_Detection_using_Image_Classification.ipynb`
- The notebook is organized step-by-step, covering data understanding, preprocessing, CNN model design, training, and evaluation.

## Model Used 🧠

The project uses a **Convolutional Neural Network (CNN)** built with TensorFlow/Keras.

Main building blocks include:

- `Conv2D` layers for feature extraction
- `MaxPooling2D` layers for dimensionality reduction
- `Flatten` and `Dense` layers for classification
- `Dropout` to reduce overfitting

## Evaluation Metrics 📊

Model performance is evaluated using:

- Accuracy
- Loss
- Confusion Matrix
- Classification Report

The output snapshots in this repository show the model summary, training curves, confusion matrix, and final classification results.

## How to Run ⚙️

1. Open `Potato_Leaf_Disease_Detection_using_Image_Classification.ipynb` in Jupyter Notebook, JupyterLab, or VS Code.
2. Install the required packages if they are not already available:
   - `tensorflow`
   - `kagglehub`
   - `matplotlib`
   - `numpy`
   - `pandas`
   - `seaborn`
   - `scikit-learn`
   - `Pillow`
3. Run the cells in order so the dataset downloads, the generators are created, and the model trains correctly.
4. Make sure you have a working internet connection for the dataset download step.

## Output Snapshots 🖼️

- Sample image from each class
<img width="1745" height="602" alt="sample image from each class" src="https://github.com/user-attachments/assets/eb0e212b-b624-47a7-8677-10c948ed66b9" />

- CNN model architecture summary
<img width="823" height="571" alt="CNN  model architecture summary" src="https://github.com/user-attachments/assets/fa3381ef-d25e-4d5b-8450-5565e9422472" />

- Model accuracy and model loss graphs
<img width="1317" height="522" alt="Model accuracy and Model loss graphs" src="https://github.com/user-attachments/assets/0378ad2f-3291-4d50-8ac0-a8895f8da806" />

- Confusion matrix heatmap
<img width="702" height="626" alt="Confusion matrix heatmap" src="https://github.com/user-attachments/assets/56fd7656-7e2b-4204-8c59-660d6cc71ab0" />

- Classification report
<img width="706" height="290" alt="Classificaiton report" src="https://github.com/user-attachments/assets/72eabc80-63c9-4176-afd0-4b14c10b0836" />

## Project Explanation Video 🎥
https://github.com/user-attachments/assets/148b2b2d-f5f4-4564-97fe-5e9a6aad7cc6

## Key Insights 💡

Based on the notebook results:

- The CNN learns useful visual features from potato leaf images.
- Training and validation accuracy improve steadily across epochs.
- The confusion matrix helps identify which classes are most often misclassified.
- The classification report provides a class-wise view of precision, recall, and F1-score.

## Author and Submission Context 👤

- **Program:** Data Science Internship at Take It Smart
- **Assignment:** Week-10 Assignment
- **Project Type:** Image Classification using CNN
