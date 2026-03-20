# MNIST Digit Recognizer

Convolutional neural network project for handwritten digit recognition using the MNIST dataset.

## Overview
This notebook builds a digit recognizer with a CNN designed for grayscale handwritten digit images. It covers data preparation, model design, augmentation, learning-rate scheduling, and evaluation through validation accuracy and confusion-matrix analysis.

## Tech Stack
- Python
- TensorFlow / Keras
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

## Workflow
1. Prepare the MNIST digit dataset
2. Normalize pixel values and format labels for multi-class classification
3. Build a CNN using convolution, max-pooling, and dropout layers
4. Improve generalization with image augmentation
5. Apply `ReduceLROnPlateau` during training
6. Evaluate on validation data and inspect the confusion matrix

## Model Notes
- Architecture pattern: `[[Conv2D -> Conv2D -> MaxPool -> Dropout] x 2] -> Flatten -> Dense -> Dropout -> Softmax`
- Optimizer: `RMSprop`
- Loss: `categorical_crossentropy`
- Regularization: dropout and learning-rate reduction

## Result
The notebook output shows validation accuracy of roughly `98.6%`.

## Files
```text
Project_Digit_Recognizer_-MNIST_Handwritten_Digits-/
├── digit_recognizer.ipynb
└── README.md
```

## Run Locally
```bash
pip install tensorflow keras numpy pandas matplotlib seaborn scikit-learn
jupyter notebook digit_recognizer.ipynb
```

## Learning Focus
- CNNs for handwritten digit recognition
- Data augmentation on image datasets
- Confusion-matrix-based error analysis
- Training stability with adaptive learning-rate scheduling
