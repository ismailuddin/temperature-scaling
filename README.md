# 🌡 Temperature scaling using TensorFlow 2
> An example of performing 🌡 temperature scaling using the TensorFlow 2.X API based
> on the paper [On Calibration of Modern Neural Networks](https://arxiv.org/abs/1706.04599)

## Overview
- A simple 🚀 [MiniVGGNet](https://www.pyimagesearch.com/2019/02/11/fashion-mnist-with-keras-and-deep-learning/) model is built and trained on the [👕Fashion MNIST 👗](https://github.com/zalandoresearch/fashion-mnist) dataset using the TensorFlow 2.X API
- The expected calibration error (ECE) is calculated and reliability diagrams plotted for the trained model
- Reusable functions provided for calculating ECE, as well as plotting reliability diagrams
- Temperature scaling is performed using **gradient descent** and the **Adam** optimiser
- Based on [PyTorch implementation](https://github.com/gpleiss/temperature_scaling) by paper authors.

## Requirements
- Python 3.X
- TensorFlow 2.X
