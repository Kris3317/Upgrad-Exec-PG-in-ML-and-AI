# Melanoma Image Classification with CNN

> This repository contains code for a Convolutional Neural Network (CNN) based project for classifying skin cancer images using TensorFlow and Keras. The goal of this project is to identify different types of skin lesions from images provided by the ISIC (International Skin Imaging Collaboration).
## Table of Contents
* [Problem Statement & Objective](#1)
* [Business Goal](#2)
* [Analysis Steps](#3)
* [Libraries Used](#4)
* [Conclusions & Recommendations](#5)
* [Acknowledgements](#6)
* [Contact](#7)

## <a name="1">Problem Statement & Objective</a>
- This project delpoys a Convolutional Neural Network (CNN) to classify images of skin lesions into various categories. The dataset contains images divided into training and testing sets
  
## <a name="2">Goal</a>
- To use the initial set of images under various classes of Melanoma and see how different CNN structures perform and it can be improved through augmentation and other processing techniques.

## <a name="3">Analysis Steps</a>
- Since there is a class imbalance evident in the dataset, we rely on data augmentation to even out the classes by performing rotation, skews and zooms on the initial dataset.

## <a name="4">Libraries Used</a>
- numpy
- pandas
- tensorflow
- matplotlib
- PIL (Python Imaging Library)
- Augmentor

## <a name="5">Conclusions & Recommendations</a>
- When the initial images alone were used the model was susceptible to overfitting due to lack of variety in the training data.
- After we augmented the data and introduced dropout layers, our model is able to perfrom well both on training & validation dataset.
  
## <a name="6">Acknowledgements</a>
- This project is a part of the Executive PG Programme in Machine Learning & AI offered by upGrad.
- [upGrad Content on CNN](https://github.com/ContentUpgrad/Convolutional-Neural-Networks/tree/main)
  
## <a name="7">Contact</a>
- Created by the [owner](https://github.com/Kris3317/) of this Repo.
- Feel free to contact me on [LinkedIn](https://www.linkedin.com/in/krismichaeldsilva/)

