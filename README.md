# Bachelor Thesis

## Automated Detection and Classification of Construction Waste Materials using YOLOv5

This repository contains the code and resources for the project on automating the detection and classification of construction waste materials using YOLOv5. The main goal is to improve the efficiency of controlling incoming waste loads at a recycling facility by replacing manual inspection with an automated machine learning approach.

## Table of Contents

Overview

Dataset

Installation

Usage

Results


## Overview
The project focuses on the following key objectives:

Collect and preprocess images of construction waste materials.
Train the YOLOv5 model on the collected dataset.
Implement real-time object detection using the trained model with an IP camera.
Send email notifications with the detected object images.

## Dataset
The dataset consists of various construction waste materials, including large stones, asphalt, metal, wood, and plastic. The images were collected using an IP camera at the company entrance. The dataset has been cleaned, labeled, and prepared for training the YOLOv5 model. It is split into training, validation, and testing sets.

## Installation
Before using the code in this repository, please ensure you have the following dependencies installed:

Python 3.x
PyTorch
torchvision
OpenCV
YOLOv5

### Clone this repository to your local machine:

`git clone https://github.com/username/your-repo.git`

### Run real-time object detection with the trained model and an IP camera:

`python detect.py --source your_ip_camera_url --weights<one of the models in /trained_models folder>`

### Send email notifications with the detected object images:

`python IDA/IDA_email.py`

## Results
The trained YOLOv5 model is capable of detecting and classifying construction waste materials in real-time. However, its performance is limited due to the lack of training data. Collecting more data and refining the model is expected to improve its performance.
