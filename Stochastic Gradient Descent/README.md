# Linear Regression from Scratch

This repository contains basic implementations of Linear Regression models from scratch using Python. The models are built without relying on any machine learning libraries, showcasing the underlying mathematics and algorithms.

## Description

In this project, we compute the parameters for a Linear Regression model using Stochastic Gradient Descent (SDG). This algorithm works great for large datasets!

## Files

- `stochastic_gradient_descent.ipynb`:
- `README.md`: Documentation of the project.

## Getting Started

### Prerequisites

- Python 3.x
- Jupyter Notebook
- Basic knowledge of Linear Regression and Python programming

### Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/cjpaine109/ai-notebooks.git
    cd ai-notebooks
    ```

2. **Install necessary packages**:
    Make sure you have the required Python packages installed. You can use `pip` to install them:
    ```bash
    pip install numpy pandas matplotlib
    ```

3. **Open Jupyter Notebook**:
    ```bash
    jupyter notebook
    ```

### Usage

1. **Navigate to the project directory**:
    ```bash
    cd Stochastic Gradient Descent
    ```

2. **Open the Jupyter Notebooks**:
    Open `stochastic_gradient_descent.ipynb` in Jupyter Notebook to run and explore the code.

## Explanation of the SGD:

Note: very similar to BGD. Some slight differences in implementation (computing gradients + random sample)

$w := w - \eta \nabla Q_{i}(w)$

Where:
- $w$ represents the weights or parameters of the model.
- $\eta$ (eta) is the learning rate, a scalar that controls the step size.
- $\nabla Q_{i}(w)$ is the gradient of the loss function $Q$ with respect to the weights $w$, computed using the $i$-th training example.

This notation indicates that the weights are updated by moving in the direction opposite to the gradient of the loss function, scaled by the learning rate.

## Note

- This implementation is intended for educational purposes.

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests for improvements or bug fixes.

## License

This project is licensed under the MIT License.

## Contact

For any questions: cjpaine109@gmail.com.
