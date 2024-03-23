# YOLOv8 Training for Road Tax Detection
This repository contains code and instructions for training a YOLOv8 model to detect road tax using the dataset provided by UTAR PRUK1 via Roboflow. The trained model can be used to detect road tax in images or videos.

# Dataset Information
The dataset used for training can be found here. It contains annotated images of Malaysian driving licenses, suitable for training object detection models.
https://universe.roboflow.com/utar-pruk1/malaysia-road-tax
![image](https://github.com/chunhonglam/Malaysia-Road-Tax-Dataset-Object-Detection-Training/assets/81572035/a4f722ea-4357-4321-abc5-728b173a3b60)

# Training Steps
Data Preprocessing: Download the dataset from the provided link. Optionally, you can use Roboflow's online platform to preprocess and augment the data.
![image](https://github.com/chunhonglam/Malaysia-Road-Tax-Dataset-Object-Detection-Training/assets/81572035/1bf18548-8d13-4850-9a10-39d9cfde5a12)

Configuration: Modify the YOLOv8 configuration file according to your requirements. Adjust parameters such as batch size, learning rate, and model architecture.
![image](https://github.com/chunhonglam/Malaysia-Road-Tax-Dataset-Object-Detection-Training/assets/81572035/42fb6f07-108a-4181-8497-2e6f8fc5fa5d)

Training: Train the YOLOv8 model using the preprocessed dataset. You can train the model locally or using cloud services like Google Colab or AWS.
![image](https://github.com/chunhonglam/Malaysia-Road-Tax-Dataset-Object-Detection-Training/assets/81572035/4f0e8016-9d53-4e9b-8462-0667685621f9)

Evaluation: Evaluate the trained model using metrics such as precision, recall, and mAP (mean Average Precision) to assess its performance.
![image](https://github.com/chunhonglam/Malaysia-Road-Tax-Dataset-Object-Detection-Training/assets/81572035/aae27cc5-33c9-4dc5-a4ac-c52087abeccc)

Deployment with Roboflow: This model can be easily deployed using Roboflow's deployment infrastructure. Roboflow provides an end-to-end platform for training, deploying, and managing computer vision models. Once trained, you can deploy your model directly from Roboflow to integrate it into your applications.

# Sample Implementation
![image](https://github.com/chunhonglam/Malaysia-Road-Tax-Dataset-Object-Detection-Training/assets/81572035/70644ce4-3124-4d20-95c0-8c8f688e7765)
