# pneumonia-classification

# Pneumonia Classification

- Link to EfficientNet model https://drive.google.com/file/d/11n1MFfRFZamLE3m605FPYN9DOIZIknue/view?usp=share_link

## Demo

We use Android Studio to deploy the application for pneumonia classification application.

The folder "DSC148Project" includes all the codes for the app.

We follow the tutorial on Image Classification App | Deploy TensorFlow model on Android | #2 for inspiration and solve the problem of how we deploying the model in the app.

We also include the apk file in this folder. You should be able to open it with any android phoen by downloading the apk file to your phone. Please only use chest x-ray as the photo input since we only train it with the chest x-ray photos.

The result returned by the app may slightly off compared with our actual model because the way we transform image to pixel matrix may not reflect the origin image itself. Since we are lacking of the related knowledge on transforming a image to pixel matrix, we heavily rely on the tutorial mentioned above.

Here is the Demo Video of our project.
