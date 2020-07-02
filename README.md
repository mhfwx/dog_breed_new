[//]: # (Image References)

[image1]: ./images/sample_dog_output.png "Sample Output"
[image2]: ./images/vgg16_model.png "VGG-16 Model Keras Layers"
[image3]: ./images/vgg16_model_draw.png "VGG16 Model Figure"


## Project Overview

This project is to develop an algorithm for dog breed identification. It will consume any user-supplied image as input and estimate the dog breed. In case a human is detected, the algorithm will estimate the dog breed that is most resembling.  

![Sample Output][image1]


## Project Requirement

numpy==1.17.0
pandas==1.0.5
python-dateutil==2.8.1
pytz==2020.1
six==1.15.0
SQLAlchemy==1.3.17


## Project Structure
All pre-processed models are saved in the bottleneck_features and the calibrated model in the save_models.

The project is in the dog_app.ipynb file.

## Project Summary

This is a Convolutional Neural Networks (CNN) project. Given an image of a dog, your algorithm will identify an estimate of the canine’s breed. If supplied an image of a human, the code will identify the resembling dog breed. The final algorithm may well be used for mobile or web face detection apps.


