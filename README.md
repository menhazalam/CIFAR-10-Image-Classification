# CIFAR-10 Image Classification

A deep learning project to classify images from the CIFAR-10 dataset into 10 categories using a Convolutional Neural Network (CNN). Built as part of the IBM AI/ML industrial training.

**About the Project:**
The CIFAR-10 dataset contains 60,000 32x32 color images (50,000 training and 10,000 testing) across 10 classes: Airplane, Automobile, Bird, Cat, Deer, Dog, Frog, Horse, Ship, and Truck.

**What was done:**
* Loaded and preprocessed the CIFAR-10 dataset in Google Colab.
* Normalized pixel values to scale them between 0 and 1.
* Built a sequential CNN using Conv2D, MaxPooling2D, and Dropout layers.
* Trained the model for 20 epochs using the Adam optimizer.
* Evaluated test performance and ran sample image predictions.

**Tech Used:**
Python, TensorFlow, Keras, NumPy, Matplotlib, Google Colab

**Results:**
* Test Accuracy: 76.1%
* Test Loss: 0.7268

**How to run:**
Open the .ipynb notebook in Google Colab or Jupyter Notebook and run all cells to view the training flow, summary, and sample predictions.
