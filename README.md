# Computational Intelligence

A collection of Python implementations exploring neural networks, unsupervised learning, associative memory, and fuzzy logic control.

## Projects

### 1. Kohonen Self-Organizing Map (SOM)

An implementation of a Self-Organizing Map from scratch that demonstrates unsupervised learning and the organization of data in a low-dimensional grid.

- Competitive learning and Best Matching Unit (BMU) selection
- Neighborhood-based weight updates
- Experiments with synthetic data and word embeddings
- Visualization of learned feature maps

**Technologies:** Python, NumPy, Matplotlib, Scikit-learn, Gensim

[Explore the implementation](./kohonen-som/)

### 2. Hopfield Network

An associative memory network that reconstructs binary patterns from noisy inputs using Hebbian learning and iterative neuron updates.

- Hebbian weight matrix construction
- Binary pattern representation
- Noise-based pattern distortion
- Pattern reconstruction and accuracy evaluation
- Visualization of original, noisy, and reconstructed patterns

**Technologies:** Python, NumPy, Matplotlib

[Explore the implementation](./hopfield-network/)

### 3. Radial Basis Function (RBF) Network

An RBF neural network implementation for classification, exploring how the selection of radial basis function centers affects model behavior.

- Gaussian radial basis functions
- Network training and prediction
- Comparison of center-selection strategies
- Evaluation using training and testing error

**Technologies:** Python, NumPy, Matplotlib, Scikit-learn

[Explore the implementation](./rbf-network/)

### 4. Fuzzy Logic Controller for Edge Computing

A simulation of fuzzy logic-based task allocation in an edge-computing environment, comparing a fuzzy controller with baseline strategies.

- Fuzzy membership functions and rule-based inference
- Simulation of multiple user devices and edge servers
- Task allocation based on delay and energy considerations
- Comparison of controller performance using simulation metrics

**Technologies:** Python, NumPy, Matplotlib, scikit-fuzzy

[Explore the implementation](./fuzzy-logic-edge-computing/)

## Technologies

- **Language:** Python
- **Numerical computing:** NumPy
- **Machine learning:** Scikit-learn
- **Visualization:** Matplotlib
- **Fuzzy systems:** scikit-fuzzy
- **Experiments:** Jupyter Notebook


## Purpose

This repository explores different approaches to computational intelligence through practical implementations and experiments. Each project focuses on a distinct technique, from unsupervised neural learning and associative memory to function approximation and fuzzy control.

