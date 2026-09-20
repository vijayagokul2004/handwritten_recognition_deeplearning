# MNIST Digit Classification using CNN

## 📌 Project Overview

This project uses a **Convolutional Neural Network (CNN)** to classify handwritten digits from **0 to 9** using the MNIST dataset.

The model is built using **PyTorch** and trained on thousands of handwritten digit images. The project demonstrates the complete deep learning workflow, including data loading, preprocessing, CNN model construction, training, evaluation, and prediction.

## 🎯 Problem Statement

Automatically recognize handwritten digits from images and classify each image into one of 10 classes:

```text
0, 1, 2, 3, 4, 5, 6, 7, 8, 9
```

## 🛠️ Technologies Used

* Python
* PyTorch
* Torchvision
* NumPy
* Matplotlib
* Google Colab

## 🧠 Model Architecture

The CNN consists of:

```text
Input Image
     ↓
Convolution Layer
     ↓
ReLU Activation
     ↓
Max Pooling
     ↓
Convolution Layer
     ↓
ReLU Activation
     ↓
Max Pooling
     ↓
Flatten
     ↓
Fully Connected Layer
     ↓
Output Layer
     ↓
10 Classes (0–9)
```

## 🔄 Project Workflow

1. Load the MNIST dataset.
2. Apply image preprocessing and normalization.
3. Create training and testing DataLoaders.
4. Build the CNN architecture using PyTorch.
5. Define the loss function and optimizer.
6. Train the model on the training dataset.
7. Evaluate the model on unseen test data.
8. Visualize predictions and model performance.

## 📊 Dataset

The project uses the **MNIST handwritten digit dataset**.

Each image is:

* Grayscale
* 28 × 28 pixels
* One of 10 digit classes

## 🚀 Training

The model is trained using:

* Loss Function: Cross Entropy Loss
* Optimizer: Adam
* Framework: PyTorch

The training process updates the model weights using backpropagation and gradient descent.

## 📈 Results

The model is evaluated using the test dataset to measure its classification performance.

### Evaluation Metrics

* Test Accuracy
* Training Loss
* Validation/Test Loss
* Sample Predictions

> Add your actual final accuracy here after training the model.

Example:

```text
Test Accuracy: XX.XX%
```

## 📁 Project Structure

```text
mnist-cnn-pytorch/
│
├── MNIST_CNN.ipynb
├── README.md
└── requirements.txt
```

## 💻 How to Run

### Google Colab

1. Open `MNIST_CNN.ipynb`.
2. Open the notebook in Google Colab.
3. Run the cells sequentially.
4. The MNIST dataset will be downloaded automatically.
5. Train and evaluate the CNN model.

### Local Environment

Install the required dependencies:

```bash
pip install torch torchvision numpy matplotlib
```

Then open the notebook using Jupyter Notebook or VS Code.

## 🔮 Future Improvements

* Add data augmentation.
* Experiment with different CNN architectures.
* Add dropout and batch normalization.
* Compare different optimizers.
* Visualize confusion matrix.
* Deploy the trained model as an API.

## 👨‍💻 Author

**A. Vijay**

B.Tech Artificial Intelligence & Data Science

## 📌 Key Learning

This project helped me understand the practical implementation of:

* CNN
* Convolution
* Pooling
* Flattening
* Activation functions
* Backpropagation
* Loss functions
* Optimizers
* Model evaluation
* PyTorch model development
