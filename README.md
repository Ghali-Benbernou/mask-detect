[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]

<!-- PROJECT LOGO -->
<br />
<p align="center">
  
  <h1 align="center">Mask-Detect</h1>

  <p align="center">
    Real-time system to detect whether the person on the webcam is wearing a mask or not. Training the face mask detector model using Keras and OpenCV.
    <br />
   
</p>

<!-- ABOUT THE PROJECT -->

## About The Project

During pandemic COVID-19, WHO has made wearing masks compulsory to protect against this deadly virus. In this tutorial we will develop a machine learning project – Real-time Face Mask Detector with Python.

Real-Time Face Mask Detector with Python
We will build a real-time system to detect whether the person on the webcam is wearing a mask or not. We will train the face mask detector model using Keras and OpenCV.

## Download the Dataset

The dataset we are working on consists of 1376 images with 690 images containing images of people wearing masks and 686 images with people without masks.

Download the dataset: https://data-flair.training/blogs/download-face-mask-data/

### Built With

We are going to build this project in two parts. In the first part, we will write a python script using Keras to train face mask detector model. In the second part, we test the results in a real-time webcam using OpenCV.

Make a python file train.py to write the code for training the neural network on our dataset. Follow the steps:

# Requirments

- [Keras](https://pypi.org/project/Keras/)
- [Tensorflow](https://pypi.org/project/tensorflow/)
- [Sv2-tools](https://pypi.org/project/cv2-tools/)
- [Numpy](https://pypi.org/project/numpy/)
- [Sklearn](https://pypi.org/project/sklearn/)

<!-- GETTING STARTED -->

## Getting Started

1-Import all the libraries and modules required.

2-Build the neural network:
This convolution network consists of two pairs of Conv and MaxPool layers to extract features from the dataset. Which is then followed by a Flatten and Dropout layer to convert the data in 1D and ensure overfitting.

3-Image Data Generation/Augmentation

4-Initialize a callback checkpoint to keep saving best model after each epoch while training

5-Train the model

Run the training:

- Python
  ```sh
  Python train.py
  ```

Run the test:
test the results of face mask detector model using OpenCV

- Python
  ```sh
  Python test.py
  ```

## Usage

if your machine is not efficient enough to run the learning:
I advise you to do it on Google colab

_Upload the "Mask_detect.ipynb" file in your Colaboratory notebook [Google Colab](https://colab.research.google.com/)_

Then run the test on your computer after you download the best trained model from Colab.

## Demo

![](img/mask_test_1.png)
![](img/mask_test_2.png)

## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request
