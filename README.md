# pneumonia-classification

# Pneumonia Classification

## Abstract
Pneumonia is a respiratory disease that affects millions of people worldwide. Early and accurate diagnosis is critical for effective treatment and management of the disease. In recent years, machine learning techniques have been increasingly used for medical image analysis, including the diagnosis of pneumonia. In this paper, we propose a pneumonia classification method using a Convolutional Neural Network (CNN) and the EfficientNet architecture. The proposed method uses chest X-ray images to distinguish between normal and pneumonia cases. We evaluated the proposed methods on a publicly available dataset (on kaggle - Chest X-Ray Images), achieving an accuracy of 76\% for the CNN and 88\% for the EfficientNet.
    Our results demonstrate the potential of using deep learning techniques for the accurate diagnosis of pneumonia, which could have significant clinical implications for the early detection and treatment of the disease.

## Demo
<p align="center">
  <img src="https://github.com/radiangle/pneumonia-classification/blob/main/demo-android.gif" alt="animated" width="250"/>
</p>

We use Android Studio to deploy the application for pneumonia classification application. 

The folder "Demo/DSC148Project" includes all the codes for the app. 

We follow the tutorial on [Image Classification App | Deploy TensorFlow model on Android | #2](https://www.youtube.com/watch?v=yV9nrRIC_R0) for
inspiration and solve the problem of how we deploying the model in the app. 

We also include the apk file in this folder. You should be able to open it with any android phoen by downloading the apk file to your phone. 
Please only use chest x-ray as the photo input since we only train it with the chest x-ray photos. 

The result returned by the app may slightly off compared with our actual model because the way we transform image to pixel matrix may not reflect the 
origin image itself. 
Since we are lacking of the related knowledge on transforming a image to pixel matrix, we heavily rely on the tutorial
mentioned above. 

Here is the [Demo Video with sound](https://youtu.be/sFSY-EhBKVY) of our project. 
