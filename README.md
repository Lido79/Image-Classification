Image Classification Model: Day or Night Recognition
This repository contains a Keras-based deep learning solution for identifying whether images represent daytime or nighttime scenes. It includes tools to apply the pre-trained model to new images.

Included Resources
predict_image.py: Execution script for image predictions

keras_Model.h5: Pre-trained model architecture and weights

labels.txt: Classification categories (day/night)

task1_output.png: Sample result demonstration

Installation
Python Version:

Compatible with Python 3.8–3.10

Required Packages:

bash
pip install tensorflow==2.19.0 keras==3.10.0 numpy pillow  
Execution
Run the prediction command:

bash
python predict_image.py your_image.jpg  
Output displays:

Identified class

Prediction certainty value

Demonstration Output:

text
Class: day  
Confidence Score: 0.91559476  
Key Attributes
Minimal setup required

Immediate predictions using pre-trained weights

Compatible with standard image formats (JPG, PNG)
