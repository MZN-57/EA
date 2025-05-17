# Neural Evolution for Handwritten Digit Recognition

## Overview
This project implements handwritten digit recognition using neural networks optimized with three approaches:
- Differential Evolution (DE)
- Differential Evolution + Genetic Algorithms (DE+GA)
- Backpropagation (BP)

The implementation is in a Jupyter Notebook (`EA_Project.ipynb`) using Python, leveraging libraries like NumPy, Matplotlib, and scikit-learn for the MNIST dataset.

## Requirements
- Python 3.x
- Jupyter Notebook
- Libraries:
  - `numpy`
  - `matplotlib`
  - `scikit-learn`
  - `pandas`

Install dependencies using:
```bash
pip install numpy matplotlib scikit-learn pandas
```

## Dataset
The project uses the MNIST dataset, which contains 70,000 grayscale images of handwritten digits (0-9), each 28x28 pixels. The dataset is automatically loaded via `scikit-learn`.

## Usage
1. Clone the repository or download `EA_Project.ipynb`.
2. Ensure all dependencies are installed.
3. Open the notebook in Jupyter:
   ```bash
   jupyter notebook EA_Project.ipynb
   ```
4. Run the cells sequentially to:
   - Load and preprocess the MNIST dataset.
   - Implement and train neural networks using DE, DE+GA, and BP.
   - Evaluate and compare model performance with visualizations.

## Structure
- **EA_Project.ipynb**: Main notebook containing:
  - Data loading and preprocessing.
  - Neural network implementation.
  - Optimization algorithms (DE, DE+GA, BP).
  - Performance evaluation and visualizations.

## Results
The notebook includes:
- Accuracy metrics for each optimization method.
- Visualizations of training progress and digit predictions.
- Comparative analysis of DE, DE+GA, and BP performance.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments
- MNIST dataset provided by scikit-learn.
- Inspired by evolutionary algorithms and neural network research.