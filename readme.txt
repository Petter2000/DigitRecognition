[Machine learning for digit recognition using Convolutional Neural Network processing the MNIST dataset]

This project presents a comprehensive PyTorch-based framework for training and evaluating a Simple Convolutional Neural Network (CNN) on the MNIST dataset, which consists of handwritten digit images. The framework encapsulates the entire machine learning workflow, including data loading, preprocessing, model definition, training, validation, and evaluation. Key components such as the number of epochs, learning rate, batch size, optimizer type, and loss function are parameterized to offer flexibility and adaptability to various experimental setups.

The model architecture, SimpleCNN, is designed with convolutional layers, max-pooling, dropout regularization, and fully connected layers to effectively learn features from the MNIST images. The training process incorporates early stopping to prevent overfitting, ensuring that the model generalizes well to unseen data. The framework also features a detailed logging mechanism that records essential metrics like precision, recall, F1 score, and validation losses, allowing for a thorough analysis of the model's performance.

Additionally, the project includes visualization utilities to display batches of images, specific digits, and incorrectly predicted instances, providing insightful diagnostics into the model's behavior. The modular and well-documented structure of the codebase makes it accessible for beginners in deep learning while offering the depth needed for more advanced experiments and research.

In summary, this project serves as both an educational tool and a practical solution for image classification tasks, demonstrating the effectiveness of CNNs and the robustness of PyTorch as a deep learning framework.

To install the required dependencies, create and activate the venv, then use command pip install -r requirements.txt