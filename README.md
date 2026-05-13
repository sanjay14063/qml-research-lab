# QML Research Lab

A research-oriented collection of quantum machine learning notebooks focused on intuition, implementation, visualization, and realistic discussion of current QML limitations.

This repository accompanies a larger QML learning platform and serves as the experimental/research side of the project.

---

## Focus Areas

This repository explores:

- Variational Quantum Circuits (VQCs)
- Quantum kernels and feature maps
- Noise-aware training on NISQ devices
- Trainability and optimization
- Quantum/classical model comparisons
- Visualization-heavy explanations of QML concepts

The goal is not to exaggerate “quantum advantage,” but to understand where quantum models may help, where they currently fail, and how modern QML systems are actually built.

---

## Notebooks

### Variational Quantum Classifier

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sanjay14063/qml-research-lab/blob/main/notebooks/variational-quantum-classifier.ipynb)

A complete walkthrough of building and training a simple VQC using PennyLane.

Topics:
- angle encoding
- variational ansatz design
- optimization
- decision boundaries
- overfitting and trainability

---

### Quantum Kernel Feature Maps

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sanjay14063/qml-research-lab/blob/main/notebooks/quantum-kernel-feature-maps.ipynb)

Compares quantum kernels against classical RBF kernels using visual kernel matrices and SVMs.

Topics:
- quantum feature maps
- kernel methods
- Hilbert space geometry
- fairness of classical vs quantum comparisons
- limits of current quantum kernel claims

---

### Noise-Aware Training

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sanjay14063/qml-research-lab/blob/main/notebooks/noise-aware-training.ipynb)

Studies how depolarizing noise affects variational quantum training and prediction quality.

Topics:
- depolarizing channels
- NISQ constraints
- unstable convergence
- noisy gradients
- hardware realism

---

## Tech Stack

- PennyLane
- Qiskit
- NumPy
- Scikit-learn
- Matplotlib
- Jupyter Notebooks

---

## Philosophy

Most beginner QML resources either:
- become mathematically inaccessible,
- oversimplify the physics,
- or overhype current capabilities.

This project attempts to sit in the middle:
- technically rigorous,
- visually intuitive,
- implementation-focused,
- and honest about limitations.

The writing style is heavily inspired by:
- 3Blue1Brown
- Quantum Computing for the Very Curious
- research-style exploratory notebooks

---

## Repository Structure

```text
qml-research-lab/
│
├── notebooks/
│   ├── variational-quantum-classifier.ipynb
│   ├── quantum-kernel-feature-maps.ipynb
│   └── noise-aware-training.ipynb
│
├── requirements.txt
└── README.md
