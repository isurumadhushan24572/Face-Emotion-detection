# Facial Emotion Recognition (FER2013)

* Welcome to the Facial Emotion Recognition project! This repository demonstrates a deep learning model that recognizes human emotions from facial expressions using the     
  FER2013 dataset. By leveraging transfer learning with the powerful ImageNet model, the model achieves an impressive 86.78% accuracy on training data.

# About the FER2013 Dataset

* The FER2013 dataset was introduced as part of a Kaggle competition, with the winning team achieving a test accuracy of 75.2%. The dataset consists of 48x48 grayscale     
  images, categorized into the following seven emotion labels:

1) Angry
2) Disgust
3) Fear
4) Happy
5) Sad
6) Surprise
7) Neutral
   
* The data is partitioned into training and testing sets for model evaluation and improvement.

# Key Features

* Transfer Learning: The model builds on pre-trained ImageNet models for high accuracy and efficient training.
* Real-Time Emotion Detection: Equipped with OpenCV, the model can predict emotions in real-time using a webcam.
* Interactive Exit Feature: Press the 'q' key to seamlessly stop the real-time prediction.
  
# How It Works

* The model analyzes facial features in real-time video streams.
* It classifies the detected face into one of the seven emotion categories.
* The predictions are displayed live on the video feed for an interactive experience.




