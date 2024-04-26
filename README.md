# MNIST Digit Recognizer

**Author**: Clement Chan, Tilova Shahrin, Calvin Chan 

**Kaggle Competition**: https://www.kaggle.com/competitions/digit-recognizer/rules 

**Data**: MNIST Data Set

## Introduction
This project is intended for the Digit Recognizer Kaggle Competition. The competition link can be found [here](https://www.kaggle.com/competitions/digit-recognizer/rules). 

## Table of Contents
- Project Overview
- Data Information
- Project Workflow
- Notebook Navigation
- Environment Setup 

## Project Overview
In this project, we explore the Modified National Institute of Standards and Technology (MNIST) data set through exploratory data analysis and predictive modelling. We use a variety of machine learning (ML) models in an attempt to classify each image to its correct number. These models include, but are not limited to, Logistic Regression, Support Vector Machines (SVMs), and neural networks such as Convolutional Neural Networks (CNNS). 

## Data Information
The data set contains images of a variety of handwritten numbers between 0-9, where each image is given as an array of 28x28 pixels, each pixel having a value between 0 and 255 representing the intensity.

## Project Workflow
This project aims to develop machine learning models for digit recognition using the MNIST dataset. The workflow involves data preprocessing, model development, training and evaluation.

## Project Structure 
    .
    ├── data/                   
    │   ├── sample_submission.csv 
    │   ├── test.csv                      
    │   └── train.csv  
    │
    ├── Notebooks/
    │   ├── MNIST_Digit_Recognizer.ipynb
    │   └── MNIST_PyTorch.ipynb
    │
    ├── requirements.txt
    │
    └── README.md

## Notebook Navigation
- MNIST_Digit_Recognizer.ipynb: Notebook containing the implementation of digit recognition using various machine learning algorithms.
- MNIST_PyTorch.ipynb: Notebook demonstrating digit recognition using PyTorch, a deep learning framework.

## Environment Setup 
To run the notebooks and reproduce the results, follow these steps:

1. Clone this repository to your local machine on your terminal.
2. Ensure you have Python and Jupyter Notebook installed.
3. Make sure you are in your cloned repository directory. 
4. Install the required dependencies by running `pip install -r requirements.txt`.
5. Run `jupyter notebook` to open the repository notebooks. 
