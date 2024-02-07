# Animal Classification with PyTorch and Transfer Learning

This repository contains a PyTorch implementation for classifying 90 different animals using transfer learning techniques. The project constits of dumpy CNN for the propose of get the right shape for matrix and pre-trained models

## Dataset

The dataset used for this project consists of images of 90 different animal species. It is structured in a way that facilitates training deep learning models for image classification tasks. Due to licensing constraints, the dataset is not included in this repository. You will need to acquire it separately and organize it into the appropriate directory structure.

## Requirements

To run the code in this repository, you need to have the following dependencies installed:

- Python 3.x
- PyTorch
- torchvision


You can install the required Python packages using pip:

```
pip install torch torchvision 
```

## Steps
# Data Transforms:

Apply appropriate data transformations such as resizing, cropping, and normalization. These transforms help in preprocessing the images before feeding them into the network for training.
# Splitting Data:

Split the dataset into training, validation, and test sets. Typically, you would use a larger portion for training, a smaller portion for validation to tune hyperparameters, and a separate test set for final evaluation.
# Build a Dummy CNN:

Before utilizing pre-trained models, build a simple Convolutional Neural Network (CNN) to ensure that the input and output shapes match the requirements. This step helps in understanding the architecture and dimensions of the network.
# Train-Validation-Test Loop:

Implement the training, validation, and test loops. During training, monitor the performance on the validation set and adjust hyperparameters accordingly to prevent overfitting. Finally, evaluate the model on the test set to assess its generalization ability.
# Import Pre-trained Models:

Import pre-trained models like VGG, DenseNet, etc., from torchvision. These models have been trained on large-scale datasets and can be fine-tuned for specific tasks like animal classification with relatively few additional training data.
## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- This project utilizes transfer learning techniques made possible by pre-trained models available in PyTorch.
- The dataset used in this project is from [https://www.kaggle.com/datasets/iamsouravbanerjee/animal-image-dataset-90-different-animals]. Please refer to the original source for licensing and usage terms.
