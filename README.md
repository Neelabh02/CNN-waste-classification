# Plastic Waste Classification using CNN
📌 Project Overview
This project aims to automate plastic waste classification using Convolutional Neural Networks (CNNs). The model classifies images of plastic waste into different categories, enabling efficient waste segregation and recycling.

# Problem Statement
Plastic waste is a major environmental issue. Proper waste classification can help improve recycling rates, reduce pollution, and enhance waste management systems. This project builds an AI-powered model that can identify and categorize plastic waste based on image inputs.

# Technologies & Tools Used
Programming Language: Python
Deep Learning Framework: TensorFlow/Keras
Libraries Used: OpenCV, NumPy, Pandas, Matplotlib, Seaborn
Data Handling: ImageDataGenerator, Data Augmentation
Model Type: Convolutional Neural Network (CNN)
Development Platform: Google Colab

# Dataset Details
The dataset consists of images categorized into two classes:

Organic Waste (non-recyclable)
Recyclable Plastic Waste
✅ Preprocessing Steps:

Images are converted to RGB format using OpenCV.
Resized to 224x224 pixels for uniform input.
Rescaled using ImageDataGenerator(rescale=1./255).
