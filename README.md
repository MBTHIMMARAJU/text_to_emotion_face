# text_to_emotion_face
about facial_emotional_face
# Facial Expression Recognition using CNN (FER-2013)

This project uses a Convolutional Neural Network (CNN) to classify facial expressions into emotions like **Happy**, **Sad**, **Angry**, **Surprise**, etc., based on grayscale facial images from the FER-2013 dataset.

## 📁 Dataset
The model is trained on the [FER-2013](https://www.kaggle.com/datasets/msambare/fer2013) dataset. The dataset contains **48x48** pixel grayscale images labeled with the following emotion classes:

- Angry
- Disgust
- Fear
- Happy
- Sad
- Surprise
- Neutral

> ⚠️ Dataset is not included in the repository. Please download it manually from Kaggle and organize it into `train/` and `test/` folders as expected by `ImageDataGenerator`.

## 🚀 Features
- Built using TensorFlow and Keras
- Trained on 48x48 grayscale images
- Supports manual emotion testing by text input
- Visualizes accuracy, loss, and prediction outputs
- Predicts emotions from test images or manual image uploads

## 🧠 Model Architecture
The CNN architecture includes:
- 3 Convolutional Blocks with Batch Normalization, MaxPooling, and Dropout
- A Dense fully connected layer
- Softmax activation for multi-class classification

## 📦 Requirements
Install necessary packages before running:

```bash
pip install tensorflow matplotlib pillow scipy
