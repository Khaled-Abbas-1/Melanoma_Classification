# Melanoma Classification: Benign vs Malignant

This project is a deep learning-based image classification system to distinguish between benign and malignant melanoma using Convolutional Neural Networks (CNNs). It leverages TensorFlow and Keras for building and training models, and Scikit-learn for evaluation.

## 🧠 Model Architecture

- Input Layer
- Convolutional Layers with LeakyReLU activation
- Batch Normalization
- MaxPooling
- Dropout Regularization
- Fully Connected Dense Layers
- Output Layer (Softmax or Sigmoid based on setup)

## 🧪 Features

- Image preprocessing and augmentation
- Train-validation split using `train_test_split`
- Support for multiple optimizers (Adam, SGD, Nadam)
- Callbacks: EarlyStopping, ModelCheckpoint, LearningRateScheduler
- Evaluation: Confusion matrix, classification report
- Visualization with matplotlib and seaborn

## 📂 Project Structure