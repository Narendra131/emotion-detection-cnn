# Emotion Detection using CNN

# Project Overview

This project uses a Convolutional Neural Network (CNN) to detect human emotions from facial images.

The trained model can classify facial expressions into different emotion categories. A real-time webcam application is also included to detect emotions from a live camera feed.

# Features

- Emotion detection using a CNN
- Facial expression classification
- Model training and evaluation
- Real-time emotion detection using a webcam
- OpenCV-based face detection
- TensorFlow/Keras model

# Technologies Used

- Python
- TensorFlow / Keras
- OpenCV
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook



# Dataset

This project uses the RAF-DB (Real-world Affective Faces Database) dataset for training the CNN model.

The dataset is not included in this repository.

The dataset should be downloaded separately and placed in the appropriate location required by the training notebook.

# Model

The project uses a Convolutional Neural Network (CNN) for facial emotion classification.

The trained model is saved as:

```
models/emotion_cnn_rafdb.h5
```

The model accepts grayscale facial images with an input size of **75 × 75 pixels**.

# Installation

Clone the repository:

```
git clone https://github.com/Narendra131/emotion-detection-cnn.git
```

Navigate to the project directory:

```
cd emotion-detection-cnn
```

Install the required dependencies:

```
pip install -r requirements.txt
```

# How to Run

# 1. Train the Model

Open the training notebook:

```
notebooks/training.ipynb
```

Run the notebook to:

- Load and preprocess the dataset
- Build the CNN model
- Train the model
- Evaluate the model
- Save the trained model

# 2. Real-Time Emotion Detection

Open the real-time detection notebook:

```
notebooks/real_time_detection.ipynb
```

The notebook loads the trained model and uses the webcam to perform real-time emotion detection.

Make sure your webcam is connected before running the notebook.

# Future Improvements

- Improve model accuracy
- Improve real-time detection performance
- Add support for more emotion categories
- Deploy the model as a web application

# Author

*Narendra131*

GitHub: https://github.com/Narendra131
