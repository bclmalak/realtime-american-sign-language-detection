# Real-time American Sign Language Detection

## Overview
This project focuses on real-time American Sign Language (ASL) detection using MediaPipe, OpenCV, pickle, scikit-learn, and NumPy. The process involves creating our own dataset, preparing the data, training a model using Random Forest, integrating the model into the main program for real-time sign detection, and evaluating its performance.

## Key Features
- **Data Collection:** Collect images for each ASL sign.
- **Data Preparation:** Extract and normalize hand landmarks with MediaPipe, organizing data into images, landmarks, and labels.
- **Model Training:** Train the model using a Random Forest classifier.
- **Real-time Detection:** Implement real-time ASL detection using OpenCV and MediaPipe.
- **Evaluation:** Assess model accuracy, perform cross-validation.
- **Hyperparameter Analysis:** Conduct hyperparameter analysis using GridSearch for model optimization.

## Used Technologies
- **MediaPipe:** Extracts hand landmarks from images.
- **OpenCV:** Accesses the camera, converts images to RGB, and performs real-time detection.
- **pickle:** Serializes and deserializes the trained model for storage.
- **scikit-learn:** Utilized for the Random Forest classifier and evaluation metrics.
- **NumPy:** Used for numerical operations and data manipulation.
