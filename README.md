# Deep-Learning-Journey
This project implements a Convolutional Neural Network (CNN) using TensorFlow/Keras to classify handwritten digits from the classic MNIST dataset.
Key Features:Data Preprocessing: Includes pixel normalization ($0-1$ range) and one-hot encoding for the $10$ digit classes.
Model Architecture: >     * Convolutional Layer: $6$ filters with a $3 \times 3$ kernel and ReLU activation.Max Pooling: $2 \times 2$ downsampling.Fully Connected Layers: A dense layer of $128$ units followed by a Softmax output layer.
Visualization: Uses Matplotlib to plot training accuracy and loss curves.
Technologies Used:PythonTensorFlow / KerasNumPyMatplotlib
