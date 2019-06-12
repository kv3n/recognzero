# Recogn Zero

## Overview
An attempt at building a visual relationship recognizer for Open Images 2019 Kaggle. Google presented a challenge on Kaggle to try and build a model for detecting visual realationships between objects detected in an image. Through Recogn Zero, we are attempting to create a simple approach to solve the problem, or at the very least understand the issues with the problem to try and build a better approach.

## Setup
- Clone the project into a directory
- Run ```python setup.py``` using any python version to create the necessary virtual environment and package dependencies. Following are the steps performed by setup.py
* Fetch Python 3.6.7, if not already present
* Create virtual environment with Python 3.6.7 as base, if not already present.
* Activate the virtual enviroment
* Install necessary package dependencies
* Setup File Structure
* Download open images dataset for Visual Relationship
* Extract the files to their respective folders

### Dependent Packages
- Tensorflow 2.0 Alpha
- OpenCV
- Matplotlib

### File Structure
- **input** - The data that will be used for training and prediction
* **training** - Training data including validation data. The code will handle the splitting
* **testing** - Data purely for testing purposes only. DON'T USE FOR TRAINING OR MODEL TUNING. This will cause PEEKING and we ain't 'bout that.
- **output** - Classification or detection results go here
* **log** - Tensorboard log files
* **debug** - Debug visualizations
* **prediction** - Prediction from the model

## Data
