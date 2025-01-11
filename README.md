# Lab Project: Neural Network Training by Transfer Learning
## Bootcamp BairesDev - Machine Learning Practitioner
## Module: Programming for Machine Learning

### Introduction
This is my first neural network training performed with transfer learning based on Keras VGG16 as part of the bootcamp Machine Learning Practitioner, offered by BairesDev through the DIO.me paltform. It is based on the Transfer Learning tutorial found at the address:  
https://colab.research.google.com/github/kylemath/ml4a-guides/blob/master/notebooks/transfer-learning.ipynb#scrollTo=3p-OjhDPYoZm  

It conssists in applying the transfer learning in a Deep Learning net using Python and the Google Colab environment.
The main goal of this work is to train a neural network to distinguish two different classes - for those I chose cats and dogs. Then, the dataset used encompasses them and may be accessed through the link:  
https://www.microsoft.com/en-us/download/details.aspx?id=54765  

The whole code and processes - from training the neural network until evaluating pictures to be recognized as a cat or a dog - are written in the file "neural_network_transfer_learning.ipynb"  
Along the way I had the opportunity to reinforce my skills in Python and Bash commands, also learning new pieces of code. All of my ideas and explanation of the processes and codes are properly commented on that file.

### Technologies
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![NumPy](https://img.shields.io/badge/NumPy-4DABCF?style=for-the-badge&logo=numpy&logoColor=fff)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-FF0000?style=for-the-badge&logo=keras&logoColor=white)

### Steps
- Getting the dataset
- Setting the images categories (directories) and the category splitting ratio
- Function for pre-processing the data into an image and input vector
- Load all the images from root folder
- Creating Training, Validation and Test splits
- Separating dataset for the training labels
- Pre-processing the data by making sure it's float32 and normalized between 0 and 1
- Transfer learning by starting with an existing network (Keras VGG16) (training)
- Ploting the results by epochs
- Predicting a new image based on the results of the transfer learning
