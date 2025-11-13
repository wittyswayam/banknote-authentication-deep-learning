# Banknote Authentication Using Deep Learning ANN

## Project Overview
This project develops an Artificial Neural Network (ANN) model to automatically classify banknotes as genuine or forged. Using features extracted from wavelet-transformed grayscale images of banknotes, the model improves the accuracy of authentication in financial and security applications.

## Dataset Description
The dataset consists of images obtained via industrial cameras used for print inspection of genuine and counterfeit banknotes. Each image, with a resolution of approximately 660 dpi and size 400x400 pixels, undergoes Wavelet Transform for feature extraction. Extracted features include:
- Variance of Wavelet Transformed Image (VWTI)
- Skewness of Wavelet Transformed Image (SWTI)
- Curtosis of Wavelet Transformed Image (CWTI)
- Entropy of Image (EI)

The dataset is labeled with a binary class: 1 for genuine banknotes and 0 for forged banknotes.

## Project Structure & Workflow
- **Data Loading & Preprocessing:** Import and prepare the dataset for model training, including normalization and handling any data quality issues.
- **Feature Exploration:** Analyze feature distributions and correlations to understand dataset characteristics.
- **Model Building:** Create an ANN using TensorFlow/Keras with input layers matching feature dimensions, one or more hidden layers with ReLU activations, and a sigmoid output layer for binary classification.
- **Training & Evaluation:** Train the model on the training set, validate on a held-out test set, and evaluate using accuracy, confusion matrix, and other metrics.
- **Results Visualization:** Graph performance metrics and feature importance insights to interpret the model behavior.
- **Potential Extensions:** Suggest CNN models for raw image input, integration of additional image processing techniques, or deployment as a real-time authentication tool.

## Usage
Run through the notebook to preprocess data, train and evaluate the ANN model, and explore results. Modify hyperparameters or architecture for experimentation.

## Results
The model achieves robust classification accuracy distinguishing genuine and counterfeit banknotes, showing potential for deployment in automated security checks and banking quality assurance processes.

[7](https://www.neuraldesigner.com/blog/banknote-authentication/)
[8](https://archive.ics.uci.edu/ml/datasets/banknote+authentication)
[9](https://cerv.aut.ac.nz/wp-content/uploads/2021/12/Ma-Yan2021_Article_BanknoteSerialNumberRecognitio.pdf)
