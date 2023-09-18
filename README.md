# Handwritten Digit Recognition with Neural Networks

This repository contains a Python project that demonstrates the creation of a neural network for recognizing handwritten digits using the MNIST dataset. The project serves as an educational example of building and training a neural network for image classification tasks.

### Objective
The primary objective of this project is to develop a neural network capable of accurately recognizing handwritten digits. The MNIST dataset, a well-known benchmark in the field of machine learning, is used for training and testing the model.

### Tools and Libraries
The project utilizes the following tools and libraries:

Python: The programming language used for the project.
NumPy: A library for numerical operations and array manipulation.
Pandas: Used for data loading and preprocessing.
Matplotlib: Employed for data visualization.
### Project Structure
The project is organized into several key components:

##### Data Loading and Preprocessing: 
The initial step involves loading the training data from a CSV file using Pandas. The data is then converted into a NumPy array and shuffled for randomness.

##### Neural Network Architecture: 
The neural network is designed with two hidden layers, each employing ReLU (Rectified Linear Unit) activation functions, and an output layer with softmax activation.

##### Training the Model: 
The neural network is trained using gradient descent to update parameters (weights and biases). Training progress is displayed, including iteration number and accuracy.

##### Making Predictions and Evaluating Accuracy: 
After training, the model is tested on both the training and development datasets. Predictions are generated, and accuracy is calculated.

##### Visualization: 
The project includes functionality to visualize the model's predictions for specific examples from the training set.



## How to Use
To run this project locally, follow these steps:

### Clone this repository to your local machine:

git clone https://github.com/manojkprabhu/digit_recognizer_from_scratch.git

### Install the required dependencies:

pip install numpy pandas matplotlib

### Navigate to the project directory:

cd digit_recognizer_from_scratch

### Execute the main script to train and test the model:
python main.py

## Results
The project demonstrates the successful creation of a neural network capable of recognizing handwritten digits with high accuracy. The model's performance is evaluated on both the training and development datasets, and predictions are visualized for better understanding.

## Conclusion
This project serves as an educational example for building and training neural networks for image classification tasks. It showcases the power of machine learning in recognizing handwritten digits and can be used as a starting point for more complex image recognition projects.

Feel free to explore the code, modify it, and learn from it. If you have any questions or suggestions, please don't hesitate to reach out.

Happy coding!
