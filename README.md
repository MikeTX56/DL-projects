# Deep Learning Projects

A collection of foundational and intermediate Deep Learning projects implemented using **Python, TensorFlow, and Keras**. This repository serves as a practical guide to understanding neural networks, from basic concepts to building complete classification pipelines.

## Repository Structure

### 1. Multi-Layer Perceptron (MLP)
**Location:** `/MLP/mlp.ipynb`

An end-to-end implementation of an Artificial Neural Network for image classification. This notebook walks through the entire deep learning workflow:
* **Data Preprocessing:** Flattening image vectors and normalizing pixel values (0-1 scaling).
* **Feature Encoding:** Implementing One-Hot Encoding for categorical target labels.
* **Model Building:** Designing a 3-layer Sequential MLP with `ReLU` hidden layers and a `Softmax` output layer.
* **Training & Validation:** Compiling the model with `categorical_crossentropy` and tracking validation metrics across epochs.
* **Evaluation:** Visualizing learning curves (loss and accuracy) and evaluating real-world performance using a Confusion Matrix.

### 2. Linear Regression with Keras & TensorFlow
**Location:** `/Linear_regression_kerasTf.ipynb`

A foundational notebook demonstrating how to use the TensorFlow/Keras framework to solve simple linear regression problems. Great for understanding the basics of neurons, weights, biases, and the fundamental Keras `Sequential` API before moving on to deep networks.

## Technologies Used
* **Python 3.x**
* **TensorFlow & Keras** (Model building and training)
* **NumPy** (Linear algebra and array manipulation)
* **Pandas** (Data handling and training history extraction)
* **Matplotlib** (Data visualization and evaluating learning curves)

## Getting Started

To run these notebooks locally on your machine, clone this repository and install the required dependencies.

**1. Clone the repository:**
```bash
git clone https://github.com/your-username/DL-projects.git
cd DL-projects
```

**2. Install dependencies:**
Make sure you have Python installed. Then, install the required libraries:
```bash
pip install tensorflow numpy pandas matplotlib jupyter
```

**3. Launch the notebooks:**
Open the repository in VS Code (which natively supports Jupyter Notebooks) or run Jupyter from your terminal:
```bash
jupyter notebook
```
