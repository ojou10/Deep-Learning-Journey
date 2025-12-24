# MNIST Handwritten Digit Classification using CNN

This project demonstrates a fundamental Deep Learning approach to classifying handwritten digits (0-9) using the **MNIST dataset**. It implements a **Convolutional Neural Network (CNN)** built with **TensorFlow** and **Keras**.



## 🚀 Project Overview
The goal of this project is to achieve high accuracy in digit recognition by leveraging spatial hierarchy in images through convolutional layers.

### Key Features:
* **Data Preprocessing**: Images are normalized to a scale of 0 to 1 for faster convergence.
* **Label Encoding**: Target labels are transformed using One-Hot Encoding via `to_categorical`.
* **CNN Architecture**: A structured approach involving feature extraction and classification layers.
* **Performance Monitoring**: Visualization of accuracy and loss trends during the training phase.

## 🏗️ Model Architecture
The model is built using the `Sequential` API and consists of the following layers:

1.  **Convolutional Layer**: $6$ filters with a $3 \times 3$ kernel, using **ReLU** activation and `same` padding.
2.  **Max Pooling**: $2 \times 2$ pool size with $2 \times 2$ strides to reduce spatial dimensions.
3.  **Flatten**: Converts the $2\text{D}$ feature maps into a $1\text{D}$ vector.
4.  **Dense Layer**: $128$ neurons with **ReLU** activation for feature interpretation.
5.  **Output Layer**: $10$ neurons with **Softmax** activation for multi-class probability distribution.

### Compilation Settings:
* **Optimizer**: `adam`
* **Loss Function**: `categorical_crossentropy`
* **Metrics**: `accuracy`

## 🛠️ Technologies Used
* **Python**: Core programming language.
* **TensorFlow / Keras**: Deep learning framework.
* **NumPy**: Numerical data processing.
* **Matplotlib**: Data visualization.

## 📊 Results
The model is trained for $10$ epochs with a batch size of $100$. The training process includes:
* Real-time accuracy tracking.
* Loss minimization analysis.
* Final evaluation on the testing dataset (10,000 images).



## 📂 How to Run
1. Clone the repository.
2. Install dependencies: `pip install tensorflow matplotlib numpy`.
3. Run the script: `python deep_learning1.py`.
