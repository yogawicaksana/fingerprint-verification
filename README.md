# Fingerprint Verification with Siamese Network

This project aims to develop a fingerprint verification model based on the Siamese network architecture using the Sokoto Fingerprint dataset. The model uses MobileNetV2 as the encoder and is trained to distinguish between two input fingerprint images and determine if they belong to the same person.

## Dataset
The dataset used in this project is the Sokoto Fingerprint dataset, which contains 6000 fingerprint images of 60 individuals with 100 images per individual. The dataset is divided into two sets, a training set with 4800 images and a test set with 1200 images.

## Files
The project consists of two main files:

1. `preprocessing.ipynb`: This file preprocesses the raw Sokoto Fingerprint dataset into a format suitable for training the Siamese network. It performs image resizing, normalization, and generates image pairs for training and validation.
2. `train.ipynb`: This file trains the Siamese network using the preprocessed dataset and evaluates the model on the validation and test sets. It also includes the code for inference using the trained model.

## Requirements
- Python 3.x
- TensorFlow 2.x
- NumPy
- OpenCV
- ImgAug
- Keras
- Matplotlib
- Seaborn

## Results
The Siamese network achieved a validation accuracy of 97% and a test accuracy of 100% on the Sokoto Fingerprint dataset. These results indicate that the model is capable of accurately verifying the identity of individuals based on their fingerprints.

## Conclusion
In conclusion, this project demonstrates the effectiveness of using a Siamese network architecture for fingerprint verification tasks. By using MobileNetV2 as the encoder, we were able to develop a model with a low number of parameters suitable for deployment on mobile and embedded devices. With further improvements in preprocessing and model optimization, the performance of the model can potentially be further improved.
