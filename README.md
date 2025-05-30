# MNIST_DIGIT_CLASSIFICATION_USING_NN
A deep learning-based project for handwritten digit recognition using the MNIST dataset, built and trained in Google Colab using Keras, NumPy, and OpenCV.

📌 Project Overview
This project focuses on building a simple yet effective Convolutional Neural Network (CNN) to classify handwritten digits (0–9) from the MNIST dataset. The model is trained using the Keras API and tested on both the built-in test data and external images processed using OpenCV.

🛠️ Technologies & Tools Used
🟦 Google Colab – For writing and executing the notebook in the cloud

🧪 Keras – For loading the MNIST dataset and building the neural network

🧮 NumPy – For handling numerical computations and array manipulations

📷 OpenCV – For preprocessing and recognizing digits from external images

📂 Dataset
MNIST Dataset: A large collection of 70,000 handwritten digits, split into:

60,000 training samples

10,000 test samples

Keras provides a preloaded version of this dataset through keras.datasets.mnist.

🧠 Model Architecture
Input Layer: 28x28 grayscale image (1 channel)

Hidden Layers:

Convolutional layers with ReLU activation

MaxPooling layers

Fully connected (Dense) layer

Output Layer: 10 neurons (softmax) for digits 0–9

📝 Trained with categorical cross-entropy loss and Adam optimizer.

🧪 Evaluation
Achieved high accuracy (~99%) on test data

Successfully classified hand-drawn digits using OpenCV preprocessing techniques
