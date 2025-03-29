# Photo Classification: Who took the photo?

A supervised classification project to predict which professor took a given photo, using deep learning and manually engineered features.

## Overview
This project explores how deep learning models can distinguish different photographers based on their image styles. We worked with a dataset of photos taken by two professors and experimented with different approaches to train models aimed at improving classification accuracy.

## Dataset & Preprocessing

* Training Set: over 200 labelled photos per photographer
* Testing Set: over 40 unlabelled photos for holdout sets 

For efficiency, I stored the file path of each image in a CSV, which enabled easy image retrieval during training.

We engineering 17 different features that included binary, numeric, and categorical variables to capture meaningful distinctions.

* **Binary Features**: Presence of people, animals, board games, camping materials, buildings, roads, and nature.
* **Numeric Features**: Number of people, number of buildings, and distance to the subject.
* **Categorical Features**: Type of animal in the image (none, pets, or exotic animals).


## Approaches & Models
### Approaches

We used these approaches to extract and identify any relevant features for classification:
1. YOLO Object Detection with Neural Network
2. Canny Edge Detection

### Models

I specifically focused on testing the following models to classify the images based on the engineered features:
1. Logistic Regression
2. Multilayer Perceptron
3. Convolutional Network
4. Ensemble with MLP and CNN

## Deliverables
In this repository, the following delivarables were produced:
* Full Dataset
* Preprocessed Data
* Trained Models
* Code and Documentation

You can find the evaluation results, report, and presentation below.

[View the Report](https://docs.google.com/document/d/1pEVgpuFxuoEakHAGJ2XrVo09N7iBm3ArtWuK6KfFeQg/edit?usp=sharing) 

[View the Presentation](https://prezi.com/view/ZCrPCJzuuVaeDIlEsxVo/)