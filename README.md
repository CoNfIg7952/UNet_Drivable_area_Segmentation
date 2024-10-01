# Drivable area Segmentation using BDK100 Dataset with UNet

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Model Architecture](#model-architecture)

## Project Overview
This project focuses on drivable area detection using the BDK100 dataset and a UNet model. The goal is to accurately identify lane lines which you can drive in, which is a critical task for autonomous driving systems.

## Dataset
unzip the segmenation.zip file to find the dataset used

## Model Architecture
I have implemented a [UNet model](link_to_UNet_paper) for drivable area segmentation. The UNet architecture consists of an encoder-decoder structure that helps in capturing both local and global information for precise segmentation.
![image](https://github.com/user-attachments/assets/a529698d-3918-41e2-a552-5286a438672d)


### Key Features:
- Encoder: Custom CNN model was used here as in the paper
- Decoder: Upsampling with skip connections
- Loss function: Dice loss
- Optimizer: Adam

to run this project locally, download and extract the segmentation.zip file, which has the required util files to run the UNet_code
