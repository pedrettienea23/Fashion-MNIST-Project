# Fashion-MNIST: CNN for Image Classification

This project focuses on building, training, and evaluating Convolutional Neural Networks (CNNs) for image classification using the Fashion-MNIST dataset. The goal was to classify Zalando's article images into 10 categories with high accuracy.

## Project Overview
Fashion-MNIST is a dataset of Zalando's article images, consisting of 60,000 training examples and 10,000 testing examples. Each image is a 28x28 grayscale image associated with one of 10 categories. This project replaces the original MNIST dataset for benchmarking machine learning algorithms.

## Key Features
- **Data Preparation**:
  - Split the training dataset into 50,000 training and 10,000 validation images.
  - Implemented a custom PyTorch dataset for better flexibility in preprocessing and augmentation.

- **Model Implementation**:
  - Designed and trained CNN architectures optimized for image classification tasks.
  - Experimented with different architectures and hyperparameters to improve model performance.

- **Evaluation**:
  - Achieved a testing accuracy of **90.17%**, demonstrating the model's reliability in classifying unseen images.
  - Reduced validation loss to as low as **0.01**, ensuring effective generalization.

- **Visualization**:
  - Visualized training and validation loss, accuracy, and sample predictions to monitor progress.

## Tools and Technologies
- **PyTorch**: Used for implementing and training CNNs.
- **Matplotlib**: For visualizing training progress and evaluation metrics.
- **Google Colab**: Utilized as the development environment with GPU acceleration.

## Dataset
The Fashion-MNIST dataset is a drop-in replacement for the original MNIST dataset. It contains:
- **Training Set**: 60,000 examples
- **Test Set**: 10,000 examples
- **Classes**: T-shirt/top, Trouser, Pullover, Dress, Coat, Sandal, Shirt, Sneaker, Bag, Ankle Boot

## Results
- Achieved a testing accuracy of **90.17%** on the test set.
- Consistently improved validation performance through architectural and hyperparameter optimization.
