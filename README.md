# Skin-Ulcer-Classification
# Skin Ulcer Classification Using CNN

## Project Overview

This project uses a Convolutional Neural Network (CNN) built with TensorFlow and Keras to classify skin images into two categories:

* **Abnormal (Ulcer)**
* **Normal (Healthy Skin)**

The goal is to explore deep learning techniques for image classification.

## Technologies Used

* Python
* TensorFlow / Keras
* NumPy
* Matplotlib
* Jupyter Notebook

## Model Architecture

The model includes convolutional layers, ReLU activations, max-pooling layers, a fully connected dense layer, dropout, and a Softmax output layer.

Image augmentation and pixel rescaling are applied as part of the model pipeline.

## Evaluation

The model was evaluated using a confusion matrix.

* **Accuracy:** 91.47%
* **Correct predictions:** 193 out of 211 evaluated images.

The confusion matrix showed:

* 85 correctly classified abnormal images.
* 108 correctly classified normal images.
* 16 abnormal images classified as normal.
* 2 normal images classified as abnormal.

These results apply to the evaluated dataset and should not be interpreted as evidence of clinical performance.

## Repository Contents

* `Skin_Ulcer_Classification.ipynb`: Notebook containing the project code and analysis.

## Disclaimer

This project is for educational purposes only. It is not a medical diagnostic tool and must not be used to make medical decisions.

