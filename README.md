# ANN-using-Pytorch
Building an Artificial Neural Network using Pytorch
ANN Classification using PyTorch

This project demonstrates the implementation of a simple Artificial Neural Network (ANN) for image classification using PyTorch.

The model is trained and evaluated on the Fashion-MNIST dataset.

Dataset

The Fashion-MNIST dataset was created by Zalando Research and contains 70,000 grayscale images of fashion items.

- Training images: 60,000
- Test images: 10,000
- Image size: 28 × 28 pixels
- Number of classes: 10
- Image type: Grayscale

Classes

Label| Class
0| T-shirt/top
1| Trouser
2| Pullover
3| Dress
4| Coat
5| Sandal
6| Shirt
7| Sneaker
8| Bag
9| Ankle boot

Dataset Source

The dataset used in this project is the Fashion-MNIST dataset by Zalando Research, available on Kaggle:

Kaggle: https://www.kaggle.com/zalando-research/fashionmnist

The original Fashion-MNIST repository is available here:

GitHub: https://github.com/zalandoresearch/fashion-mnist

Project Overview

In this project, a basic Artificial Neural Network is built using PyTorch to classify Fashion-MNIST images into one of the 10 clothing categories.

The workflow includes:

1. Loading the Fashion-MNIST dataset
2. Data preprocessing
3. Converting images into tensors
4. Creating the ANN architecture
5. Defining the loss function
6. Defining the optimizer
7. Forward propagation
8. Calculating the loss
9. Backpropagation
10. Updating model parameters
11. Training the model
12. Evaluating the model on test data

Technologies Used

- Python
- PyTorch
- Torchvision
- NumPy
- Matplotlib
- Google Colab

Model

The Artificial Neural Network is implemented using PyTorch's "torch.nn" module.

The input image contains:

28 × 28 = 784 pixels

These pixels are flattened and provided as input to the neural network.

The final layer produces 10 outputs, corresponding to the 10 Fashion-MNIST classes.

Running the Project

The complete implementation is available in:

"Building_ANN_using_PyTorch.ipynb"

The notebook can be opened and executed using Google Colab.

Dataset Handling

The Fashion-MNIST dataset does not need to be uploaded to this repository.

It can be downloaded automatically using the PyTorch/Torchvision dataset API when the notebook is executed.

Results

The notebook contains the training process, loss/accuracy results, and model evaluation.

Author

Rashi Pandey
