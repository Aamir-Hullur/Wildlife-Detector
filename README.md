# WildlifeDetector

## Project Overview
WildlifeDetector is a deep learning project that automates the classification of wildlife images from camera traps. Using advanced models like ResNet-101 and InceptionV3, this project distinguishes between 'Blank' and 'Not Blank' images to support wildlife research and conservation.

## Model Architecture
![Model Architecture](https://raw.githubusercontent.com/Aamir-Hullur/Wildlife-Detector/main/Images/Model_architecture.png)

The above diagram illustrates the workflow of our image classification process. Starting from a large dataset of camera trap images, we manually label the data into three categories: Animals, Blank, and Humans. Post labeling, the images undergo data preprocessing which includes resizing and normalization. The processed data then feeds into our ConvNet models, ResNet101 and InceptionV3, for training. The model's performance is evaluated using a separate set of test images.

## Features
- Efficient classification of over 100,000 camera trap images.
- Implementation of state-of-the-art deep learning models.
- Significant enhancement in accuracy and reduction of manual effort for wildlife image analysis.

## Data
The dataset is large; hence, only a sample is included in the `Dataset Preview/` directory.
