# Gradient Descent for Linear Regression

This repository contains implementations of gradient descent algorithms for linear regression, including both stochastic and batch methods. Gradient descent is an optimization algorithm used to minimize the cost function in linear regression, effectively addressing the computational inefficiencies of Ordinary Least Squares (OLS) in high-dimensional data scenarios.

PS - The pdf file contains handwritten notes and more explaination about gradient descent.

## Key Concepts Covered

- **Gradient Descent**: An iterative optimization technique designed to find the minimum of a cost function by adjusting parameters in the direction of the steepest descent.
- **Learning Rate**: A crucial hyperparameter that controls the size of the steps taken towards the minimum. Proper tuning of the learning rate is essential for efficient convergence.
- **Cost Function**: Mean Squared Error (MSE) is utilized to measure the difference between predicted and actual values.
- **Stopping Criteria**: Convergence is determined when parameter updates become minimal or after reaching a predefined number of iterations.

## Types of Gradient Descent

- **Batch Gradient Descent**: Computes gradients using the entire dataset in each iteration. While this method provides stable updates, it can be computationally expensive and slow for large datasets.
- **Stochastic Gradient Descent (SGD)**: Updates parameters using individual data points. This approach offers faster convergence and requires less memory but can exhibit noisy updates.
- **Mini-Batch Gradient Descent**: Uses small, random subsets of data (mini-batches) for each update. This method combines the advantages of both Batch and Stochastic Gradient Descent, providing a balance between speed and accuracy.

## Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/priyagupta18/gradient-descent.git
2. Navigate to the project directory:

   ``` bash
   cd gradient-descent
3. Install the required dependencies:

   ``` bash
   pip install -r requirements.txt
4. Launch Jupyter Notebook:

   ``` bash
   jupyter notebook
