# 🚦 Traffic Sign Classification with Machine Learning

Welcome to this project on **Traffic Sign Recognition** using machine learning and computer vision!

## Project Goal

The goal of this project is to build a machine learning model that can automatically recognize and classify different traffic signs from images. This is especially useful in the development of self-driving vehicles and intelligent traffic systems.
The data set gives a good idea of working with visual data for machine learning and feature extraction from images. 

The dataset consists of thousands of traffic sign images captured in real-world conditions, such as:
- Good and poor lighting
- Partially obscured signs
- Signs at various distances from the camera

The images were pre-processed (cropped, scaled) and stored in a Python object. Each image has an associated label, and a CSV file contains the mapping of label indices to traffic sign names.

The original unprocessed dataset was sourced from [Kaggle](https://www.kaggle.com). The pre processed data set is from [GitHub User Emanueliarussi](https://github.com/emmanueliarussi/DataScienceCapstone/tree/master/3_MidtermProjects/ProjectRTS).

## What This Notebook Does

- Loads and visualizes traffic sign image data
- Extracts features using **Histogram of Oriented Gradients (HOG)** 
- Trains and evaluates a **Support Vector Machines (SVM)**
- Compares model performance using:
  - Accuracy
  - Confusion matrix (pending)
- Tests generalization on unseen data

## Requirements

Make sure you have the following Python libraries installed:
- `numpy`
- `matplotlib`
- `scikit-learn`
- `opencv-python`
- `seaborn`
- `pickle`
