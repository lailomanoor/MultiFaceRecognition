# MultiFaceRecognition
This project focuses on multiple face detection and localization in test images, given training images of individual people. It utilizes Haarcascade for training due to its speed and efficiency, and MTCNN for testing to ensure accuracy.

## Introduction
The MultiFaceDetectionLocalization project aims to detect and localize multiple faces in a given test image using a model trained on individual people's images. The project leverages Haarcascade for face detection during training and MTCNN for more precise detection during testing.

## Features
- Multiple face detection and localization
- Utilizes Haarcascade for efficient training
- Uses MTCNN for accurate face detection in testing
- Supports real-time face recognition


## Usage
### Training the Model
1. Place the training images in the `dataset` directory, organized in subdirectories named after each individual.

2. Update the base_dir variable in the script to the relative path of the dataset directory.

### Testing the Model
1. Update the test_image_path or test_folder_path variable in the script to reflect the relative path to the test image or test images folder.
