
# MNIST Handwritten Digit Classification Using Neural Networks

📌 Project Overview

This project uses a Neural Network to classify handwritten digits from the MNIST dataset.

The model is trained to recognize digits from 0 to 9 based on grayscale images of handwritten numbers.

🎯 Project Objectives

- Load and explore the MNIST dataset.
- Preprocess and normalize the image data.
- Build a Neural Network using TensorFlow/Keras.
- Train the model on handwritten digit images.
- Evaluate the model using test data.
- Visualize model predictions.
- Compare different learning rates.
- Compare different optimizers.
- Compare different batch sizes.

📊 Dataset

The project uses the MNIST Handwritten Digit Dataset.

The dataset contains:

- 60,000 training images.
- 10,000 test images.
- Each image has a size of 28 × 28 pixels.
- There are 10 classes, representing digits from 0 to 9.

🧠 Model Architecture

The Neural Network consists of:

- Input layer: 784 features
- Dense layer: 128 neurons, ReLU activation
- Dense layer: 64 neurons, ReLU activation
- Output layer: 10 neurons, Softmax activation

⚙️ Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Google Colab
- Jupyter Notebook

🔬 Experiments

The project includes experiments to study the effect of:

Learning Rate

Different learning rates are compared to observe their effect on model performance.

Optimizers

The following optimizers are compared:

- SGD
- Adam
- RMSprop

Batch Size

Different batch sizes are tested and their effect on the model's test accuracy is analyzed.

📈 Evaluation

The model is evaluated using:

- Test Loss
- Test Accuracy
- Prediction visualizations

📁 Project Structure

MNIST-Neural-Network/
│
├── MNIST.ipynb
└── README.md

🚀 How to Run

1. Open "MNIST.ipynb".
2. Open it using Google Colab or Jupyter Notebook.
3. Run the cells from top to bottom.
4. The dataset will be downloaded automatically through TensorFlow/Keras.

👨‍💻 Project

MNIST Handwritten Digit Classification Using Neural Networks

This project demonstrates a complete Deep Learning workflow, from data preprocessing to model training, evaluation, and experimentation
