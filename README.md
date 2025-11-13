# 💵 Banknote Authentication Using Deep Learning ANN 🤖

## 🚀 Project Overview
This project uses an Artificial Neural Network (ANN) to classify banknotes as **genuine** or **forged** based on features extracted from wavelet-transformed images. It automates banknote authentication, improving security in financial transactions and counterfeit detection.

***

## 📊 Dataset Description
The dataset consists of grayscale images (400x400 px, ~660 dpi) from an industrial print inspection camera. Features extracted using Wavelet Transform include:

| Feature | Description                   |
|---------|-------------------------------|
| VWTI    | Variance of Wavelet Transformed Image       |
| SWTI    | Skewness of Wavelet Transformed Image       |
| CWTI    | Curtosis of Wavelet Transformed Image       |
| EI      | Entropy of Image                           |

The labels indicate:

- 🟢 Genuine banknotes (Class 1)  
- 🔴 Forged banknotes (Class 0)

***

## 🔧 Project Workflow

### 1. Data Loading & Preprocessing  
- Import dataset and clean data  
- Normalize features for ANN input

### 2. Exploratory Data Analysis  
- Visualize feature distributions  
- Plot correlations  

<img src="images/feature_distribution.png" alt="Feature Distribution" width="600"/>

### 3. ANN Model Building  
- Fully connected neural network using TensorFlow/Keras  
- Input layer corresponds to 4 extracted features  
- Hidden layers with ReLU activation  
- Output layer with sigmoid activation for binary classification  

### 4. Model Training & Evaluation  
- Split data into training and test sets  
- Train model with suitable epochs and batch size  
- Evaluate using accuracy, confusion matrix, precision, recall  

<img src="images/confusion_matrix.png" alt="Confusion Matrix" width="400"/>  

***

## 🎯 Usage
- Detailed step-by-step workflow in the Jupyter notebook  
- Modify ANN architecture or hyperparameters to experiment  
- Visualize results for interpretability  

***
