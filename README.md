# Three Hidden Layer Neural Network for Multi-Class Classification

## Introduction
This project implements a three hidden layer neural network for multi-class classification. The task involves modifying the provided codebase to accommodate the multi-class classification problem and evaluating the model's performance.

## Dataset Generation
- A synthetic dataset is generated with five distinct classes.
- The dataset includes input features suitable for training a neural network.

## Implementation
- Extend the `NeuralNetwork` class to support multi-class classification.
- Update the output layer to have five neurons, each corresponding to one class.
- Modify the activation function and loss calculation to suit the multi-class scenario.
- Adapt the backpropagation algorithm to handle multiple classes.

## Training and Testing
- Split the generated dataset into training and testing sets.
- Train the neural network using the training data.
- Evaluate the performance of the trained model using the testing data.

## Performance Metrics
- Accuracy
- Precision
- Recall
- F1-Score

## Results and Analysis
The performance of the neural network model was evaluated using different configurations, each varying in the number of hidden layers and learning rate.

### Configuration 1
- Hidden Layers: (10, 10, 10)
- Learning Rate: 0.2
- Accuracy: 0.21
- Precision: 0.0441
- Recall: 0.21
- F1 Score: 0.0729

### Configuration 2
- Hidden Layers: (20, 20, 20)
- Learning Rate: 0.1
- Accuracy: 0.2
- Precision: 0.04
- Recall: 0.2
- F1 Score: 0.0667

### Configuration 3
- Hidden Layers: (5, 5, 5)
- Learning Rate: 0.3
- Accuracy: 0.2
- Precision: 0.04
- Recall: 0.2
- F1 Score: 0.0667

**Observation:** Configuration 1 with three hidden layers of 10 neurons each and a learning rate of 0.2 shows slightly better performance compared to other configurations.

## Challenges Encountered and Lessons Learned
- Model performance fell below expectations, highlighting the complexity of multi-class classification.
- Tuning hyperparameters, dataset complexity, and result interpretation were challenging but emphasized the importance of experimentation, data quality, and thorough evaluation.

## Potential Improvements and Further Experiments
- Explore data augmentation, advanced architectures like CNNs or RNNs, and automated hyperparameter optimization.
- Incorporate regularization techniques and ensemble methods for improved model robustness and performance.

## Installation and Execution

### Prerequisites
- Anaconda with Jupyter Notebook
- VS Code with Jupyter extension

### Steps

1. **Jupyter Notebook:**
    - Open the notebook.
    - Run the code cells sequentially.

2. **VS Code:**
    - Open the `.py` file.
    - Run the code.

The results will be displayed in the output section.

## Conclusion
This project highlights the implementation of a three hidden layer neural network for multi-class classification. Despite the challenges and suboptimal performance, the exercise provided valuable insights into neural network design and the importance of careful tuning and evaluation. Further improvements and experiments are necessary to enhance model performance for multi-class classification tasks.
