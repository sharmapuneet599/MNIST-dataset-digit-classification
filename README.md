# MNIST-dataset-digit-classification
## Project : Recognizing hardwritten digits

In this project we will discover the MNIST handwritten digit recognition problem and we will develop a deep learning model in Python using the Keras library that will be capable of achieving excellent results. Now some questions come to mind:
- What is deep learning ? 
- Deep Learning is a subfield of machine learning concerned with algorithms inspired by the structure and function of the brain called artificial neural networks.
- Why we are using keras ?
- Keras is one of the best neural network Frameworks currently around. Here are the main advantages I see for it:
  - Simplicity (code itself is very good)
  - Awesome community - there is good documentation, lots of community code, it is also the framework of choice for many Kagglers nowadays meaning you can get a constant stream of some really insightful data science competition grade code written in keras.
  - Very active development.
- What is MNIST handwritten digit recognition problem ?
- The MNIST problem is a dataset developed by Yann LeCun, Corinna Cortes and Christopher Burges for evaluating machine learning models on the handwritten digit classification problem.The dataset was constructed from a number of scanned document dataset available from the National Institute of Standards and Technology (NIST). This is where the name for the dataset comes from, as the Modified NIST or MNIST dataset. Images of digits were taken from a variety of scanned documents, normalized in size and centered. This makes it an excellent dataset for evaluating models, allowing the developer to focus on the machine learning with very little data cleaning or preparation required. In this tutorial, we’ll give you a step by step walk-through of how to build a hand-written digit classifier using the MNIST dataset. For someone new to deep learning, this exercise is arguably the “Hello World” equivalent. It consists of 70,000 labeled 28x28 pixel grayscale images of hand-written digits. The dataset is split into 60,000 training images and 10,000 test images. There are 10 classes (one for each of the 10 digits). The task at hand is to train a model using the 60,000 training images and subsequently test its classification accuracy on the 10,000 test images.

## Libraries used:
- Numpy
- Keras
- matplotlib

## Evaluation 
The model gets loss a of 0.0241 and an accuracy of 0.992 while evaluating on the test set.
