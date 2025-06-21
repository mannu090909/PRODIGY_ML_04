# ✋ PRODGIGY_ML_04 - Hand Gesture Recognition with CNN

This project builds a Convolutional Neural Network (CNN) to recognize hand gestures using the **LeapGestRecog** dataset.

## 📁 Dataset
- Source: [Kaggle - LeapGestRecog](https://www.kaggle.com/datasets/gti-upm/leapgestrecog)
- Contains grayscale images of various hand gestures performed by users.

## 🚀 Features
- Image loading and preprocessing using OpenCV
- Label encoding of gesture classes
- CNN architecture built with TensorFlow/Keras
- Model training, evaluation, and accuracy visualization

## 📊 Technologies Used
- Python
- OpenCV
- NumPy
- Matplotlib
- TensorFlow/Keras
- Google Colab

## 🧠 Model Overview
- 2D Convolutional layers
- MaxPooling
- Dropout for regularization
- Dense output layer with softmax activation

## 📷 Sample Image
![gesture](https://raw.githubusercontent.com/mannu090909/PRODIGY_ML_04/main/sample_image.png)

## 📈 Results
- Accuracy: ~xx% (you can add actual value after training)
- Loss & accuracy graphs visualized using matplotlib

## 🛠 How to Run
1. Clone the repo or open in Google Colab
2. Upload your Kaggle API token
3. Run all cells in order

```bash
!kaggle datasets download -d gti-upm/leapgestrecog
