# Convolutional Neural Network for Image Classification

This repository contains a Python script that implements a Convolutional Neural Network (CNN) for image classification using PyTorch. The CNN model is designed to classify images into different categories based on the provided dataset from Kaggle.

## Dependencies

- Python >= 3.6
- PyTorch
- torchvision
- numpy

## Dataset

The dataset used for this project is located in the `obrazki/` directory. It consists of images categorized into different classes.

## Data Preprocessing

The images are preprocessed using the following transformations:
- Resize the images to a size of 128x128 pixels.
- Convert the images to PyTorch tensors.
- Normalize the image data by applying mean and standard deviation normalization.

## Loading and Splitting Data

The data is loaded using PyTorch's `ImageFolder` dataset class. It is split into training and testing sets using data loaders.

## CNN Architecture

The Convolutional Neural Network (CNN) model used for image classification consists of multiple convolutional layers followed by pooling layers, fully connected layers, and dropout layers for regularization.

## Model Training

The CNN model is trained using the training dataset. The training process involves forward and backward passes through the network, optimization using gradient descent, and updating the model parameters.

## Model Evaluation

After training, the model is evaluated using the testing dataset. The accuracy and performance metrics are calculated to assess the effectiveness of the trained model in classifying images.

## Acknowledgments

This code is inspired by various online resources on Convolutional Neural Networks for image classification.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
