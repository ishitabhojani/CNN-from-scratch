# CNN from scratch
## Pre-requirements:
    1. Intermediate level knowledge of Python libraries numpy and  pandas
    2. Basic Fundamentals for Understanding Convolutional Neural Networks
    3. Mathematics for creating the functions of questions.
## Technologies and Libraries Used:
Python: Core programming language for implementing the model and algorithms.
NumPy: Essential for numerical computations and matrix operations.
Pandas: Utilized for data handling and preprocessing.
Matplotlib: Used for data visualization and plotting model performance metrics.

## Project Description:
I implemented a Convolutional Neural Network (CNN) from scratch using Python and core libraries such as NumPy, Pandas, and Matplotlib. The goal was to build a CNN model for classifying handwritten digits from the MNIST dataset, providing a comprehensive learning experience in deep learning, mathematics, and neural network architecture.

## Features and Learning Outcomes:
### 1. Data Preparation and Preprocessing:
        - Imported and analyzed the MNIST dataset using Pandas for exploratory data analysis
        - Imported and analyzed the MNIST dataset using Pandas for exploratory data analysis.
        - Split the dataset into training and testing sets to evaluate model performance effectively.
### 2. Building CNN Architecture from Scratch:
1. Convolutional Layers:
       
        I have implemented multiple convolutional layers to extract spatial features from input images, applying various filters to detect edges, textures, and patterns.
2. Activation Functions:

        Incorporated Rectified Linear Units (ReLU) to introduce non-linearity, allowing the network to learn complex patterns.
3. Pooling Layers:

         Used Max Pooling layers to reduce spatial dimensions, preventing overfitting and lowering computational costs.

4. Fully Connected Layers:

        Built fully connected layers (dense layers) to interpret the features learned by the convolutional layers and output the final classification.


### 3. Forward and Backward Propagation:

    Developed algorithms for forward propagation to compute the output of each layer in the network.
    I have Implemented backward propagation to update network weights and biases based on the gradient descent optimization technique.
    To Utilize the cross-entropy loss function to measure the difference between the predicted and actual outputs, adjusting weights to minimize this loss during training.


### 4. Visualization and Analysis:

    I Used Matplotlib to visualize training progress, including loss and accuracy curves, providing insights into model performance and potential overfitting.
    To Visualize feature maps after each convolutional layer to understand how the model interprets input data at different stages.

    
### 5. Model Evaluation:

    Evaluated model performance on the test dataset, achieving high accuracy in digit classification.
    TO Calculate various performance metrics, such as precision, recall, F1-score, and confusion matrix, to provide a comprehensive evaluation of the model's strengths and weaknesses.
    To Analyze misclassified examples to understand failure modes and improve model robustness.

This Notebook was a valuable learning experience that provided an in-depth understanding of the inner workings of Convolutional Neural Networks. Building a CNN from scratch without the use of high-level deep learning libraries such as TensorFlow or PyTorch enhanced my understanding of the underlying mathematical principles and computational processes in deep learning.


