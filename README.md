# Flower-classification-assignment

# Reproducing Training and Graph

## Introduction

This guide provides instructions on how to reproduce the training of a deep learning models and generate training graphs for flower classification of 104 types. experimentation is done with pre-trained architectures (InceptionV3, MobileNetV2, VGG16) with additional trainable layers.

## Prerequisites

Make sure you have the following installed:

- Python (version >= 3.6)
- TensorFlow (version >= 2.0)
- Jupyter Notebook (for running the provided code)

## Steps

1. **Download Pre-trained Models and Add Custom Trainable Layers:**

    Uncomment the code sections related to downloading and layer addition in the Jupyter Notebook. This is typically located under the "Downloading the Pre-trained Models and Adding Custom Trainable Layers" markdown cell.

2. **Run the Training Cells:**

    Execute the cells below the downloading section to start the training process. This will involve training the model using the specified dataset and configurations.

3. **Generate Training Graphs:**

    Run the code located under the "Plots Between Training and Validation Accuracies During Training" markdown cell. This will produce graphs showing the training and validation accuracies over epochs.
