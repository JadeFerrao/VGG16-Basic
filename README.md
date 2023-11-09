# VGG16-Basic

## Description
# This project demonstrates the implementation of a deep learning model for image classification/regression tasks.

## Installation
# Ensure you have Python 3.6+ installed. Clone the repository and install the required packages using the following command on collab:
# pip install -r requirements.txt

#### Model Built from Scratch Using Rooms Dataset
# 1. Data Preparation: The rooms dataset includes images of various room types. Data augmentation techniques were used to increase the dataset size.
# 2. Model Architecture: The model is built from scratch using the VGG-16 architecture with modifications to suit the room classification task.
# 3. Training: The model was trained using the prepared dataset for 10 epochs with a batch size of *.

#### Pre-trained Model (Keras) Using Diabetes Retinopathy Dataset
# 1. Data Preparation: The diabetes retinopathy dataset was preprocessed, and images were formatted to match the input requirements of the pre-trained model.
# 2. Pre-trained Model: The pre-trained model used is based on the VGG-16 architecture, pre-trained on the ImageNet dataset.
# 3. Fine-tuning: The pre-trained model was fine-tuned using transfer learning techniques for the specific task of diabetes retinopathy classification.

## Results
# The model achieved an accuracy of 56% on the rooms dataset and 0.75 for the diabetes retinopathy dataset.

## License
# This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Acknowledgments
# Special thanks to the contributors of the rooms dataset and the diabetes retinopathy dataset via kaggle.
