# Exploring Activation Functions in Deep Learning

Welcome to the repository for the project "Exploring Activation Functions in Deep Learning". This project aims to explore the impact of different activation functions on the performance of a neural network using the MNIST dataset.

## Project Overview

In this project, we compare three popular activation functions: **Sigmoid**, **Tanh**, and **ReLU**. The main goal is to evaluate their performance in terms of accuracy when applied to a simple neural network model for classifying handwritten digits from the MNIST dataset.

### Activation Functions Used:
1. **Sigmoid**: \[Accuracy: 97.69%\]
2. **Tanh**: \[Accuracy: 97.65%\]
3. **ReLU**: \[Accuracy: 97.75%\]

### Dataset
The MNIST dataset is used for training and testing. This dataset consists of 60,000 training images and 10,000 test images of handwritten digits (0-9).

### Model Architecture
The model used in this project is a simple feedforward neural network with the following architecture:
- **Input Layer**: 784 neurons (28x28 flattened pixel values)
- **Hidden Layer**: 128 neurons
- **Output Layer**: 10 neurons (one for each digit class)

### Results
The results of the experiment show that the **ReLU** activation function performs slightly better than **Sigmoid** and **Tanh** in terms of accuracy. This is consistent with the widespread adoption of ReLU in modern neural networks due to its ability to mitigate the vanishing gradient problem.

## Visualizations
![Accuracy Comparison](![output](https://github.com/user-attachments/assets/ddbd4643-3ebf-4fc6-ad93-e247cc747305))  
The bar chart above shows the comparison of accuracy for each activation function. 

## Installation

To run the code in this repository, make sure you have the following dependencies installed:

```bash
pip install tensorflow pandas seaborn matplotlib numpy
```
## Usage
1. Clone this repository:
```bash
git clone https://github.com/AryanMithbawkar/Exploring-Activation-Functions-in-Deep-Learning.git
```
2. Navigate to the project directory:
```bash
cd Exploring-Activation-Functions-in-Deep-Learning
```
3. Run the Jupyter notebook or Python scripts to see the experiments and results.

## Conclusion
This project demonstrates the importance of choosing the right activation function in deep learning models. While the differences in accuracy are small, the choice of activation function can impact model performance, especially in larger, more complex networks.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments
Special thanks to the developers and contributors of TensorFlow and Keras, whose tools were essential in the completion of this project.# Exploring-Activation-Functions-in-Deep-Learning
