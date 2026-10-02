# 🧠 Deep Learning & Neural Networks Curriculum

[![Python 3.9+](https://img.shields.io/badge/python-3.9+-blue.svg)](https://www.python.org/downloads/)
[![PyTorch](https://img.shields.io/badge/PyTorch-2.0+-ee4c2c.svg)](https://pytorch.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![CUDA Supported](https://img.shields.io/badge/CUDA-Accelerated-green.svg)](https://developer.nvidia.com/cuda-zone)

A comprehensive, 6-week hands-on curriculum covering deep learning fundamentals—ranging from mathematical intuition and Perceptrons to PyTorch implementations, GPU training, and modern optimizer architectures.

---

## 📌 Table of Contents
- [Curriculum Overview](#-curriculum-overview)
- [Weekly Breakdown](#-weekly-breakdown)
- [Repository Structure](#-repository-structure)
- [Tech Stack & Prerequisites](#-tech-stack--prerequisites)
- [Getting Started](#-getting-started)
- [License](#-license)

---

## 🗺️ Curriculum Overview

| Week | Module | Topic / Focus Area |
| :---: | :--- | :--- |
| **Week 1** | **Module 01** | Introduction to Deep Learning and Perceptrons |
| | **Module 02** | How Perceptrons Learn – Intuition, Code, and Edge Cases |
| | **Module 03** | Decision Boundaries and Perceptron Learning |
| **Week 2** | **Module 04** | Learning in Perceptrons – From Gradient Descent to Loss Functions |
| | **Module 05** | From Activation to Loss Function |
| | **Module 06** | Foundations of Multi-Layer Perceptrons and Forward Propagation |
| | **Module 07** | **DL Assignment 01** |
| **Week 3** | **Module 08** | Backpropagation Fundamentals |
| | **Module 09** | PyTorch Basics and Backpropagation Implementation |
| | **Module 10** | From Computation Graph to Autograd Implementation |
| **Week 4** | **Module 11** | PyTorch Training Pipeline From Scratch |
| | **Module 12** | PyTorch `nn` Module & `torch.optim` |
| | **Module 13** | Training Dynamics in PyTorch – Batch, SGD & Mini-Batch |
| | **Module 14** | **DL Mid Term Exam** |
| **Week 5** | **Module 15** | Deep Learning Project Setup (Dataset and DataLoader in PyTorch) |
| | **Module 16** | From ANN Implementation to GPU Training with PyTorch |
| | **Module 17** | Loss Functions and Training Challenges in Deep Neural Networks |
| **Week 6** | **Module 18** | Data Scaling, Standardization, and Normalization |
| | **Module 19** | Batch Normalization |
| | **Module 20** | Optimizers |

---

## 📚 Weekly Breakdown

### 🔹 Week 1: Perceptron Fundamentals & Linear Decision Boundaries
* **Module 01:** Introduction to Deep Learning, history, and single-layer artificial neurons (Perceptron).
* **Module 02:** Geometric intuition of Perceptron training, edge cases, and building a Perceptron classifier from scratch in Python.
* **Module 03:** Linear separability, hyperplanes, and mathematical limits of single-layer decision boundaries.

### 🔹 Week 2: Loss Functions & Multi-Layer Perceptrons
* **Module 04:** Mathematical formulation of error surfaces, loss functions, and introduction to gradient descent.
* **Module 05:** Non-linear activation functions (Sigmoid, Tanh, ReLU) and their relationship to continuous loss minimization.
* **Module 06:** Architecture of Multi-Layer Perceptrons (MLPs), hidden layer feature extraction, and forward pass dynamics.
* **Module 07:** **DL Assignment 01** — Implementation and evaluation of multi-layer neural architectures.

### 🔹 Week 3: Backpropagation & Computational Graphs
* **Module 08:** Derivation of the backpropagation algorithm using the multivariate chain rule.
* **Module 09:** PyTorch Tensor fundamentals, memory layout, and manual backpropagation step implementation.
* **Module 10:** Directed Acyclic Graphs (DAGs), dynamic computation graphs, and automatic differentiation using `torch.autograd`.

### 🔹 Week 4: PyTorch Pipelines, Optimization & Assessment
* **Module 11:** Designing a modular PyTorch training loop from scratch (Forward, Loss, Backpropagation, Step).
* **Module 12:** Encapsulating neural layers using `torch.nn.Module` and optimizing weights using `torch.optim`.
* **Module 13:** Comparison of batch gradient descent, Stochastic Gradient Descent (SGD), and mini-batch dynamics.
* **Module 14:** **DL Mid Term Exam** — Theoretical assessment and practical coding exam.

### 🔹 Week 5: Data Pipelines, GPU Acceleration & Training Challenges
* **Module 15:** PyTorch data engineering—building custom `Dataset` classes, configuring `DataLoader`, batching, and memory pinning.
* **Module 16:** Transferring models and tensors to CUDA hardware (`.to(device)`), inference acceleration (`torch.no_grad()`), and `model.eval()` mode.
* **Module 17:** Loss function selection strategies and handling training bottlenecks (vanishing/exploding gradients, overfitting).

### 🔹 Week 6: Feature Scaling, Normalization & Advanced Optimizers
* **Module 18:** Pre-processing input data using Min-Max scaling, Z-score standardization, and its impact on the loss landscape.
* **Module 19:** Internal Covariate Shift, Batch Normalization (`nn.BatchNorm1d` / `2d`), layer positioning, and train vs. test behaviors.
* **Module 20:** Modern optimization algorithms—Momentum, RMSprop, Adam, AdamW, and hyperparameter tuning best practices.

---

## 📁 Repository Structure

```text
.
├── Week 01: Perceptron Fundamentals/
├── Week 02: Multi-Layer Perceptrons & Loss Functions/
├── Week 03: Backpropagation & PyTorch Basics/
├── Week 04: Training Pipelines & Dynamics/
├── Week 05: Project Setup & GPU Acceleration/
├── Week 06: Normalization & Optimizers/
└── README.md
