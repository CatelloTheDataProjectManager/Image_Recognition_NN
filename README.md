# Image Recognition using Neural Networks

This repository contains multiple notebooks for deep learning projects focused on image recognition. Each notebook corresponds to a specific project.

## Notebook Contents

1. **[MLP_CNN_MNIST.ipynb](https://github.com/CatelloTheDataProjectManager/neural_networks/blob/main/MLP_CNN_MNIST.ipynb)**
    - **Description**: This notebook uses a Multi-Layer Perceptron (MLP) and a Convolutional Neural Network (CNN) for classifying images from the MNIST dataset.
    - **Dataset**: MNIST (handwritten digit images)
    - **Models**: MLP, CNN
    - **Results**: Accuracy and learning curves for each model.

2. **[CNN_CIFAR.ipynb](https://github.com/CatelloTheDataProjectManager/neural_networks/blob/main/CNN_CIFAR.ipynb)**
    - **Description**: This notebook implements a Convolutional Neural Network (CNN) for classifying images from the CIFAR-10 dataset.
    - **Dataset**: CIFAR-10 (32x32 color images across 10 classes)
    - **Models**: CNN
    - **Results**: Accuracy, confusion matrices, and learning curves.

3. **[MLP_CNN_malaria_cell_images.ipynb](https://github.com/CatelloTheDataProjectManager/neural_networks/blob/main/MLP_CNN_malaria_cell_images.ipynb)**
    - **Description**: This notebook combines a Multi-Layer Perceptron (MLP) and a Convolutional Neural Network (CNN) for classifying cell images from the Malaria Cell Images dataset.
    - **Dataset**: Malaria Cell Images (healthy and infected cell images)
    - **Models**: MLP, CNN
    - **Results**: Accuracy, confusion matrices, and learning curves for each model.

4. **[RNN.ipynb](https://github.com/CatelloTheDataProjectManager/neural_networks/blob/main/RNN.ipynb)**
    - **Description**: This notebook uses a Recurrent Neural Network (RNN) for a time series prediction task.
    - **Dataset**: Time series data (to be specified)
    - **Models**: RNN (including LSTM, GRU, etc.)
    - **Results**: Prediction curves and performance 

5. **[YOLO_LabelStudio.ipynb](https://github.com/CatelloTheDataProjectManager/Image_Recognition_NN/blob/main/Train_YOLO_Models_(Fire).ipynb)**
    - **Description**: This notebook demonstrates how to train an object detection model using the YOLO architecture with custom annotations exported from Label Studio. It includes automatic generation of the `data.yaml` config file, model configuration (e.g., choosing YOLOv5, YOLOv8, or YOLO11 variants), training setup, and evaluation on a validation dataset. The workflow is fully integrated with the Ultralytics YOLO library, allowing quick experimentation with various model sizes and resolutions.
    - **Dataset**: Custom-labeled dataset (Label Studio export format)
    - **Models**: YOLOv5, YOLOv8, or YOLO11 (s/m/l/xl variants)
    - **Results**: mAP, precision, recall, training metrics per epoch, and sample predictions on validation images.
  
    <p float="left">
      <img src="https://github.com/CatelloTheDataProjectManager/Image_Recognition_NN/blob/main/fire_80.jpeg?raw=true" alt="Sample Prediction 1" height="350"/>
      <img src="https://github.com/CatelloTheDataProjectManager/Image_Recognition_NN/blob/main/fire_82.jpeg?raw=true" alt="Sample Prediction 2" height="350"/>
    </p>


