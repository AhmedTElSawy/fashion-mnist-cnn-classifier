# Fashion MNIST CNN Classifier

TensorFlow/Keras Convolutional Neural Network (CNN) for classifying images from the Fashion MNIST dataset (e.g., shirts, shoes, bags).

## Overview
- **Dataset**: Fashion MNIST (60,000 training + 10,000 test images, 28×28 grayscale, 10 classes).
- **Model**: Convolutional Neural Network  
  Conv2D(32) → Conv2D(64) → MaxPool → Conv2D(128) → MaxPool → Flatten → Dense(128, ReLU) + Dropout(0.5) → Dense(10, Softmax).
- **Training**: Adam optimizer (learning rate = 0.0005), categorical cross-entropy loss, early stopping (patience=5).
- **Results**: **92.35% test accuracy**, 0.2179 test loss.

## How to Run
1. Clone the repo: `git clone https://github.com/AhmedTElSawy/fashion-mnist-cnn-classifier.git`
2. Install dependencies: `pip install -r requirements.txt`
3. Open and run the notebook: `jupyter notebook fashion-mnist-cnn.ipynb`

## Dependencies
- TensorFlow/Keras
- Numpy/Scipy
