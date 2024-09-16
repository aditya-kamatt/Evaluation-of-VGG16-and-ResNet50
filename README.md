# Evaluation of VGG16 and ResNet50

This project evaluates and compares the performance of two popular convolutional neural network architectures, **VGG16** and **ResNet50**, for image classification tasks. The project involves data preparation, model loading, and testing on pre-trained models to assess their accuracy and efficiency.

## Project Structure
- `Loading_Data.ipynb`: Notebook for loading and preprocessing data.
- `Data_Preparation.ipynb`: Code for preparing the dataset for training and evaluation.
- `ResNet50_Model.ipynb`: Implementation of ResNet50 model evaluation.
- `Evaluating_and_Testing_Pre_Trained_Models.ipynb`: Final evaluation and comparison of both models.
- `classifier_resnet_model.h5`: Saved weights for the ResNet50 model.
- `classifier_vgg16_model.h5`: Saved weights for the VGG16 model.

## Requirements
- Python 3.x
- TensorFlow
- Keras
- NumPy
- Matplotlib

## Usage
Clone the repository:
   ```bash
   git clone https://github.com/aditya-kamatt/Evaluation-of-VGG16-and-ResNet50.git
   ```
Install the required libraries:
  ```bash
    pip install -r requirements.txt
  ```
Run the notebooks to load data, train, and evaluate the models.

## Results
The final evaluation compares VGG16 and ResNet50 based on:

- Accuracy
- Model complexity (parameters)
- Inference speed
