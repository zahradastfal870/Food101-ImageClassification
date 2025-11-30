Food101-ImageClassification
Deep Learning Project – CS-5710

Instructor: Dr. I-Hua Tsai
Team Members:

Zahra Dastfal

Umesh Chander Reddy

Vinod Kumar Reddy

📌 Project Overview

This project applies Deep Learning techniques to classify food images from the Food-101 dataset.
We implement:

A baseline CNN model

Transfer learning using EfficientNetB0

Fine-tuning for improved performance

Model training visualization (accuracy & loss curves)

Confusion matrix to analyze misclassification

Evaluation metrics: Accuracy, Loss, F1-Score

📁 Project Structure
Food101-ImageClassification/
│
├── code/                 # Jupyter Notebook (.ipynb) – main code
├── plots/                # Training curves + confusion matrix
├── report/               # Final written project report (PDF/DOCX)
├── slides/               # Final presentation slides (PPT/PDF)
└── README.md             # Project overview

📊 Models Implemented
1️⃣ Baseline CNN

Convolution → MaxPool layers

Trained from scratch

Lower accuracy (expected)

2️⃣ EfficientNetB0 (Transfer Learning)

Pretrained ImageNet weights

Feature extractor mode

Accuracy improved significantly

3️⃣ EfficientNetB0 (Fine-Tuned)

Unfroze top layers

Best performance among all models

🧪 Dataset

Food-101 Dataset

101 food categories

1,000 images per class

75,750 for training / 25,250 for testing

Images loaded with TensorFlow preprocessing

🛠️ Tools & Libraries

Python

TensorFlow / Keras

NumPy

Matplotlib

Scikit-learn

Google Colab (GPU T4)

📈 Results Summary

EfficientNetB0 + Fine-Tuning achieved the highest accuracy.

Clear performance improvement shown in training curves.

Confusion matrix helped identify difficult classes.

(Plots are available in the plots/ folder.)

🚀 How to Run

Install dependencies:

pip install tensorflow numpy matplotlib scikit-learn


Open the notebook:

code/Food101_DeepLearning_Project.ipynb


Run all cells.

📝 Notes

The notebook includes full comments for readability.

The report and slides follow the course project requirements.

All work is original and unplagiarized
