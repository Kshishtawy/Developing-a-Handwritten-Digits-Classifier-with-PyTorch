# Handwritten Digits Classifier with PyTorch

## Project Overview

This project focuses on developing a robust neural network using PyTorch to accurately classify handwritten digits. The main aim was to achieve a remarkable accuracy of at least 90% on the test set. The project involved loading the dataset, preprocessing the data, constructing and training a neural network, evaluating its accuracy, and finally, saving the trained model.

## Project Notebooks

For an in-depth walkthrough and detailed explanations, refer to the comprehensive Jupyter Notebook file: [MNIST_Handwritten_Digits-STARTER-main.ipynb](MNIST_Handwritten_Digits-STARTER-main.ipynb).

## Project summary

### Step 1: Dataset Loading and Preprocessing

The dataset was loaded from torchvision.datasets. PyTorch transforms and methods were employed to convert the data into tensors, apply normalization, and flatten the data. A DataLoader was created to efficiently handle the dataset.

### Step 2: Dataset Visualization and Exploration

Visualization played a crucial role. The dataset was visualized using a provided function and explored without normalization or flattening. This exploration allowed for an understanding of the natural and transformed appearances of the inputs. The documentation provides a brief justification for any preprocessing steps or explanations if no preprocessing was needed.

### Step 3: Neural Network Construction and Training

The core of the project involved the construction of a PyTorch neural network capable of predicting the class of each input image. An optimizer was carefully selected to update the network’s weights, and the training DataLoader was used to effectively train the neural network.

### Step 4: Model Evaluation

Once trained, the neural network’s accuracy on the test set was evaluated. Model hyperparameters and network architecture were tuned to improve accuracy, with the ultimate goal of achieving at least 90%.

### Step 5: Trained Model Saving

To ensure the model's reusability, torch.save was used to save the trained model.

## Model Accuracy

The model was able to achieve an outstanding accuracy of 96.54% on the test set.

## This was the second project of the "Udacity Machine Learning Fundamentals Nandegree" offered by AWS as part of the "AWS AI & ML scholarship"
Confirmation  link: [link](https://graduation.udacity.com/confirm/e/ba2b0610-ee8f-11ed-8e43-fbdc25fcc49f)

## License

This project is licensed under the [MIT License](LICENSE).
