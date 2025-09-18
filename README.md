# 🖊️ Digit Recognizer (MNIST Handwritten Digits)

A machine learning project to recognize handwritten digits (0–9) using the **MNIST dataset**.  
This project demonstrates data preprocessing, model training, and evaluation for image classification.  

---

## 📌 Project Overview

The MNIST dataset is a collection of **70,000 grayscale images** (28x28 pixels) of handwritten digits.  
The goal of this project is to build a machine learning model that can accurately classify these digits.  

This project includes:
- Exploratory Data Analysis (EDA)  
- Data preprocessing and normalization  
- Model training (ML/DL approach)  
- Performance evaluation with accuracy and visualizations  
- Predictions on unseen test data  

---

## 📂 Dataset

- **Source:** [MNIST dataset (Kaggle)](https://www.kaggle.com/c/digit-recognizer)  
- **Train Set:** 42,000 labeled digit images  
- **Test Set:** 28,000 unlabeled digit images  
- **Image Size:** 28x28 pixels, grayscale  

---

## ⚙️ Project Workflow

1. **Data Loading** – Import CSV dataset into Pandas DataFrame  
2. **Preprocessing** – Normalization, reshaping, and one-hot encoding of labels  
3. **Modeling** – Training ML/DL classifiers (e.g., CNN, RandomForest, Logistic Regression)  
4. **Evaluation** – Checking accuracy, confusion matrix, and visual predictions  
5. **Results** – Best model achieves high accuracy (>98% with CNN)  

---

## 🛠️ Technologies Used

- **Programming Language:** Python 3  
- **Libraries:**
  - `numpy`, `pandas` → Data processing  
  - `matplotlib`, `seaborn` → Visualization  
  - `scikit-learn` → ML models and metrics  
  - `tensorflow` / `keras` → Deep Learning models (CNN)  

---

## 🚀 Installation

Clone this repository:

```bash
git clone https://github.com/yourusername/digit-recognizer.git
cd digit-recognizer
