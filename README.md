# Diabetic-Ratinopathy

Dataset : https://www.kaggle.com/c/diabetic-retinopathy-detection/data
The content extracted from the file contains code snippets related to building and training a Convolutional Neural Network (CNN) using TensorFlow and Keras. Here's a brief summary based on the content:

---

### Project Title: **Diabetic Retinopathy Detection Using CNN**

### Description:
This project involves building a Convolutional Neural Network (CNN) model to detect and classify the severity of diabetic retinopathy from medical images. The model is trained on a dataset of retinal images and aims to assist in the early detection and treatment planning for diabetic patients.

### Key Components:

1. Dataset Preparation:
   - Utilizes TensorFlow's `image_dataset_from_directory` for loading and preprocessing images.
   - The dataset is split into training, validation, and testing sets.

2. Model Architecture:
   - The CNN model includes layers such as `Conv2D`, `MaxPooling2D`, and `Dense` layers with ReLU activation.
   - The model is designed to handle images resized to a specific dimension with normalization.

3. Training:
   - The model is trained over 150 epochs with a batch size of 26.
   - Techniques such as caching, shuffling, and prefetching are employed to optimize training performance.

4. Evaluation:
   - The trained model is evaluated on validation and test datasets to assess its accuracy in classifying diabetic retinopathy.

### Installation and Usage:
To run this project, ensure you have TensorFlow installed and access to a suitable GPU for faster training.

---
