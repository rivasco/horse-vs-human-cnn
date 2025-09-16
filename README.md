# Horse vs Human Classifier

A convolutional neural network (CNN) built with TensorFlow and Keras with pooling layers to classify images as horses or humans.

## Features

- Preprocesses images with `image_dataset_from_directory` and normalizes them using a `Rescaling` layer.
- CNN with convolutional, pooling, and dense layers ending in a sigmoid activation for binary classification.
- Trains efficiently with RMSProp optimizer and `binary_crossentropy` loss.
- Handles datasets with varying image sizes and formats.
- Supports testing with custom images from the internet.
- Visualizes intermediate layer outputs to understand features learned by the network.

## Overview

This project demonstrates a complete pipeline from raw images to a trained binary classifier. Images are preprocessed for consistency, passed through a CNN to extract features, and classified as horse or human. Pooling layers reduce spatial dimensions while preserving important features, and intermediate visualization provides insight into what the network has learned.

Any horses or human dataset can be used, such as this one: https://www.kaggle.com/datasets/sanikamal/horses-or-humans-dataset.
