GitHub Repository Description:

Project Name: Image Classification with Convolutional Neural Networks

Description:

This GitHub repository contains code for a Convolutional Neural Network (CNN) model designed for image classification. The model is trained to classify images as either 'dog' or 'cat' based on a dataset provided in CSV format. The code uses the TensorFlow and Keras libraries for building and training the neural network.

Key Components:

Data Preparation: The script loads image data and corresponding labels from CSV files ('input.csv' and 'labels.csv' for training, 'input_test.csv' and 'labels_test.csv' for testing). The data is reshaped and normalized by scaling pixel values to a range between 0 and 1.

Model Architecture: The CNN model architecture is defined using Keras Sequential API. It consists of convolutional layers, max-pooling layers, and fully connected layers. The model aims to learn relevant features from the input images.

Training: The model is trained using the training data with a binary cross-entropy loss function and the Adam optimizer. The training process consists of 5 epochs, and the batch size is set to 64.

Evaluation: The trained model's performance is evaluated using the test dataset. The script calculates the loss and accuracy of the model on the test data.

Prediction: After training, the model is used to predict the class of a random test image, and the prediction is displayed along with the image.
