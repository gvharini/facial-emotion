**facial-emotion**
🎭 Facial Emotion Recognition using CNN

This project builds a Facial Emotion Recognition (FER) system using a Convolutional Neural Network (CNN) in TensorFlow/Keras.
It detects human emotions from facial images and classifies them into categories like Happy, Sad, Angry, Neutral, Fear, Surprise, and Disgust.

📘 Project Overview

The goal of this project is to train a deep learning model to recognize human emotions from facial expressions.
We use a publicly available Facial Emotion Recognition Dataset from Kaggle and build a CNN model to classify emotions based on facial features.

⚙️ Installation and Setup

1. Download the dataset
import kagglehub
path = kagglehub.dataset_download("fahadullaha/facial-emotion-recognition-dataset")

2. Install dependencies
pip install kaggle tensorflow keras opencv-python numpy matplotlib

os.environ['KAGGLE_USERNAME'] = "username"   # <-- Replace with your Kaggle username -->
os.environ['KAGGLE_KEY'] = "kagglekey"  # <-- Replace with your Kaggle kagglekey -->



