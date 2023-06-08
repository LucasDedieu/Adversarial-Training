# Adversarial Training on CIFAR Classification with PyTorch

This repository contains a notebook that implements adversarial training on CIFAR classification using PyTorch. The goal of this project is to train a classification model without adversarial training and then attack it using the projected gradient descent (PGD) attack. The accuracy of the model is compared with and without adversarial training, and data augmentation techniques are also applied.

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Adversarial training is an important technique in the field of deep learning, especially in improving the robustness of models against adversarial attacks. In this notebook, we explore the process of training a classification model on the CIFAR dataset using PyTorch. We then apply adversarial training to enhance the model's ability to withstand attacks such as the PGD attack.

Additionally, we incorporate data augmentation techniques to improve the model's generalization and performance. By comparing the accuracy of the model before and after adversarial training, we can assess the effectiveness of this technique in enhancing robustness.

## Installation

You can install the required dependencies by running the following command:

```
pip install requirements.txt
```
## Usage
Clone the repository and navigate to the project directory.

Launch Jupyter Notebook.

Open the adversarial-training.ipynb notebook.

Follow the instructions in the notebook to execute the code cells.

## Results
The notebook will guide you through the following steps:

Data preprocessing: Loading and augmenting the CIFAR dataset.

Model training: Training a classification model without adversarial training.

Adversarial attack: Performing a projected gradient descent (PGD) attack on the trained model.

Adversarial training: Retraining the model using adversarial examples.

Evaluation: Comparing the accuracy of the model before and after adversarial training.

The results, including accuracy comparisons and visualizations, will be discussed within the notebook itself.

## Contributing
Contributions to this project are welcome. If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.
