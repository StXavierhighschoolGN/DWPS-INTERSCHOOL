# Sign Language to Text and Speech Conversion
## A Smart Solution for Inclusive Communication
**Presented by St. Xaviers High School, Greater Noida West**

### Table of Contents
1. [Introduction](#introduction)
2. [Project Purpose](#project-purpose)
3. [Features](#features)
4. [System Requirements](#system-requirements)
5. [Installation](#installation)
6. [Usage](#usage)
7. [Dataset Information](#dataset-information)
8. [Technical Details](#technical-details)
9. [Team Members](#team-members)
10. [References](#references)
### Introduction
This project aims to bridge the communication gap between the deaf and hearing communities by translating American Sign Language (ASL) gestures into readable text and audible speech. Our innovative solution empowers individuals to communicate effortlessly, fostering inclusivity and accessibility.

### Project Purpose
Designed to translate ASL gestures into text and speech, this project is ideal for various environments, including schools, workplaces, and hospitals. Our goal is to enable individuals with hearing impairments to communicate more freely and accurately.

### Features
- **Real-time Gesture Recognition**: Detects and identifies hand signs from live video input.
- **Text Conversion**: Converts recognized gestures into readable text output.
- **Speech Output**: Reads out recognized gestures, making communication accessible to all.
- **User-Friendly Interface**: Easy-to-use and intuitive interface designed for all age groups.

### System Requirements
- **Operating System**: Windows 10 or 11
- **Python Version**: 3.11
- **Hardware**: Webcam for real-time gesture detection, 4GB+ RAM

### Installation
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-repository/Sign-Language-To-Text-and-Speech-Conversion.git
2. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
3. **Enable Long Path Support**
**Important Note**
"image_path": "C:/path/to/your/project/images/white.jpg"
make sure you modify the path in the following code
### Note
The scripts `data_collection_binary.py` and `data_collection_final.py` are not required if you already possess a trained model file and do not plan on making future modifications to the model.
Other wise you will have to change image path in these codes

### Usage
1. **Run the application**:S
   ```bash
   python prediction_gui.py

### Dataset Information
This model was trained on a dataset of ASL signs, including letters A-Z and additional controls (space, nothing, and delete).
### Technical Details
**Model Architecture:** **Convolutional Neural Network (CNN) for gesture classification.**
**Libraries Used:** **OpenCV, Keras, TensorFlow, and cvzone for efficient hand detection and recognition.**
### Team Members 
**Lead Developer: Dhairya Singh**
### References
https://docs.opencv.org/4.x/index.html
https://google.github.io/mediapipe/solutions/hands
https://www.tensorflow.org/tutorials/images/cnn