# Melanoma Image Classification (Benign vs Malignant)

This project uses Convolutional Neural Networks (CNNs) built with TensorFlow and Keras to classify skin lesion images into **Benign** or **Malignant** categories.

🧠 Model Overview

•	Uses Conv2D layers with BatchNorm, LeakyReLU, MaxPooling, and Dropout.
•	Binary classification (Benign = 0, Malignant = 1)
•	Optimizers used: Adam, SGD, Nadam
•	Evaluated using confusion matrix, accuracy, and classification report

## 🧪 Features

- Image preprocessing and augmentation
- Train-validation split using `train_test_split`
- Support for multiple optimizers (Adam, SGD, Nadam)
- Callbacks: EarlyStopping, ModelCheckpoint, LearningRateScheduler
- Evaluation: Confusion matrix, classification report
- Visualization with matplotlib and seaborn

## 📊 Dataset
•	The dataset is split into train/, validation/, and test/ directories
•	Each contains subfolders Benign/ and Malignant/

## 🚀 Running the Model

Use the notebook Model_1_2_3.ipynb to train and evaluate different models and optimizers.

## 📈 Evaluation
•	Training/Validation accuracy and loss plots
•	Confusion matrix and classification report
•	Can integrate with callbacks like EarlyStopping, ModelCheckpoint, and LearningRateScheduler

## 🛠️ Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/melanoma-classification.git
   cd melanoma-classification
   ```

2. Ensure you have [uv](https://github.com/astral-sh/uv) installed.

3. Install dependencies after you make the environment:

```bash
uv venv
uv pip install -e .
```

Or using requirements.txt:

```bash
uv pip install -r requirements.txt
```

---

📄 License

This project is open-source and available under the MIT License.
