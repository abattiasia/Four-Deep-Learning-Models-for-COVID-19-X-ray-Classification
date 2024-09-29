# Four-Deep-Learning-Models-for-COVID-19-X-ray-Classification
Four Deep Learning Models for COVID-19 X-ray Classification

## Introduction
In the context of the ongoing COVID-19 pandemic, accurate and timely diagnosis is critical to controlling the spread of the virus. X-ray images have proven to be an important tool for detecting COVID-19-induced pneumonia. In this project, I applied several deep learning models to the **COVID19-Xray-Dataset** to predict COVID-19 cases from X-ray images. The models employed include **Convolutional Neural Networks (CNN)**, **VGG16**, **VGG19**, and **MobileNetV3**.

## Dataset Overview
The dataset consists of labeled X-ray images categorized into COVID-19 positive and negative cases. The images underwent pre-processing to ensure uniform size and normalization, suitable for input into deep learning models.

## Methodology
The study used the following models for training and evaluation:

1. **Convolutional Neural Network (CNN)**: A simple CNN architecture was designed with multiple convolutional and pooling layers followed by fully connected layers for classification.
   
2. **VGG16**: A deep convolutional network with 16 layers, VGG16 is known for its high performance on image classification tasks.
   
3. **VGG19**: Similar to VGG16 but with a deeper architecture consisting of 19 layers, VGG19 often improves performance by capturing more complex patterns.
   
4. **MobileNetV3**: MobileNetV3 is a lightweight, efficient architecture designed for mobile and edge devices, making it well-suited for environments with limited computational resources. It strikes a balance between model size and accuracy.

Each model will be trained on the same pre-processed dataset, with hyperparameters such as learning rate and batch size optimized for each model. The dataset was split into training, validation, and test sets for robust evaluation.


![image](https://github.com/user-attachments/assets/47a9bc74-b712-4258-821d-ee58ca79cc0d)
