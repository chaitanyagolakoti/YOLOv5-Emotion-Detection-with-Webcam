# YOLOv5 Emotion Detection
This repository contains a custom-trained YOLOv5 model for detecting emotions on faces. The model has been trained to recognize five different emotions: anger, drowsy, fear, happy, neutral, and sad. It was trained on a dataset of 150 images for 600 epochs.

## Table of Contents
1. Introduction
2. Dataset
3. Training
4. Evaluation
5. Results

## Introduction
Emotion detection on faces is a vital application in various fields, including human-computer interaction, healthcare, and sentiment analysis. This project utilizes the popular YOLOv5 object detection framework, adapted for emotion recognition.

## Dataset
The emotion detection model was trained on a custom dataset comprising 150 images labeled with the corresponding emotions: anger, drowsy, fear, happy, neutral, and sad. The dataset is included in this repository and corresponding lables for the images too, but you can create your own or use publicly available datasets.

## Training
To train the YOLOv5 model on your custom dataset, follow these steps:

1. Prepare your dataset in the required format, placing the images in the data/images/ directory and the corresponding labels in the data/labels/ directory.
2. Modify the data.yaml file in the data/ directory to specify the number of classes (emotions) and the path to your training and validation datasets.
3. Start training
4. The trained model and logs will be saved in the runs/ directory, in your pc.

## Evaluation
1. In the dataset.yaml file itself I provided the links for train, test, validate but for the additional evaluation,
2. I took images from the web which has a lot of different emotion images
3. Those images images helped me to evaluate my model more accurately.

## Results
The real-time emotion detection results will be displayed on the webcam feed, showing bounding boxes around detected faces and labels indicating the predicted emotions.

## Contributing
Contributions to this project are welcome. If you find any issues or want to add new features, please create a pull request, and we will review it.

