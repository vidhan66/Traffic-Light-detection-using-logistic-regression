# Traffic Light Classification with Logistic Regression

This project classifies traffic lights in images into three classes: **Red**, **Yellow**, and **Green**. It uses a **Logistic Regression** model for classification. Additionally, it provides real-time traffic light prediction using a webcam feed to control a simulated bot's actions based on the traffic light color.

## Project Overview

This project demonstrates the use of computer vision and machine learning to predict traffic light colors in images and use those predictions to control a bot. The bot follows these rules based on the predicted traffic light:
- **Red Light**: Stop the bot.
- **Yellow Light**: Prepare to stop.
- **Green Light**: Move the bot forward.

### Project Structure

The dataset is structured into three main categories:
- **train**: Contains images and corresponding labels used for training the model.
- **valid**: Contains images and labels used for validating the model during training.
- **test**: Contains images and labels used for evaluating the model's performance.

Each directory contains two subdirectories:
- **images**: Contains the traffic light images.
- **labels**: Contains the corresponding label files with class IDs (`0` for Red, `1` for Yellow, `2` for Green).

### Dataset Format
- **Images**: `.jpg` or `.png` format.
- **Labels**: Each label file is a `.txt` file containing class IDs for the respective image. The first number in the label file represents the class ID:
  - `0` for Red
  - `1` for Yellow
  - `2` for Green

## Installation 

### Prerequisites

- Python 3.x
- Libraries: `numpy`, `scikit-learn`, `opencv-python`, `pillow`


