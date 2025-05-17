# Neural Evolution for Handwritten Digit Recognition

Hey there! Welcome to my project where I dive into recognizing handwritten digits using some cool neural network tricks. I’ve played around with three different ways to train the network, and I’m excited to share it with you!

## What’s This About?
This project is all about teaching a neural network to read handwritten digits (like 0-9) from the MNIST dataset. I’ve tried three approaches to make the network smarter:
- **Differential Evolution (DE)**
- **Differential Evolution + Genetic Algorithms (DE+GA)**
- **Backpropagation (BP)**

Everything’s coded up in a Jupyter Notebook (`EA_Project.ipynb`) using Python, with a little help from NumPy, Matplotlib, and scikit-learn.

## What You’ll Need
To run this project, you’ll need:
- Python 3 (any recent version should do).
- Jupyter Notebook to open the `.ipynb` file.
- A few Python libraries:
  - `numpy` (for number crunching)
  - `matplotlib` (for pretty plots)
  - `scikit-learn` (for the MNIST dataset)
  - `pandas` (for data handling)

Get them installed with:
```bash
pip install numpy matplotlib scikit-learn pandas
```

## The Data
I’m using the **MNIST dataset**, which has 70,000 images of handwritten digits, each 28x28 pixels. It’s a classic dataset for machine learning, and scikit-learn makes it super easy to load.

## How to Run It
1. Grab the repo by cloning it or downloading `EA_Project.ipynb`.
2. Make sure you’ve got all the libraries installed (see above).
3. Run Jupyter Notebook:
   ```bash
   jupyter notebook EA_Project.ipynb
   ```
4. Run the cells one by one. You’ll see the code:
   - Load and prep the MNIST data.
   - Build and train the neural network with DE, DE+GA, and BP.
   - Show off the results with some neat graphs and accuracy scores.

## What’s Inside
- **EA_Project.ipynb**: The heart of the project, with:
  - Code to load and preprocess the MNIST dataset.
  - A neural network built from scratch.
  - The three optimization methods (DE, DE+GA, BP).
  - Visualizations to compare how each method does.

## What You’ll See
The notebook spits out:
- Accuracy scores for each training method.
- Graphs showing how the network learns over time.
- A side-by-side comparison of DE, DE+GA, and BP to see which one is better.
