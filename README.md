# Grokking Deep Learning

<p align="left">
  <img src="https://img.shields.io/badge/Python-3.1x-9B7EDC?style=for-the-badge&logo=python&logoColor=white" alt="Python 3.8–3.12">
  <img src="https://img.shields.io/badge/Deep%20Learning-Assignment%2002-B39DDB?style=for-the-badge" alt="Deep Learning Assignment 02">
  <img src="https://img.shields.io/badge/Computer%20Engineering-Telkom%20University-C3B1E1?style=for-the-badge" alt="Computer Engineering, Telkom University">
</p>

This repository contains structured chapter summaries, theoretical explanations, code reproductions, and practical implementations based on the book:

**Grokking Deep Learning**
by *Andrew W. Trask (Manning Shelter Island)*

The project is developed as part of the **Deep Learning** course at **Telkom University**, focusing on understanding the fundamental principles of deep learning through conceptual analysis, mathematical intuition, and hands-on Python implementation.

***Status: Work in Progress.***

---

# Project Overview

This repository provides a structured learning resource that integrates theoretical understanding with practical implementations, designed to enhance comprehension and application of deep learning concepts in academic and practical contexts.

Each chapter is documented through **Python‑based Jupyter Notebooks** containing summaries, objectives, theoretical explanations, code reproductions, annotated implementations, result interpretations, and discussions to support both conceptual clarity and applied experimentation.

The content follows the original book’s organization while adding explanatory notes and demonstrations to clarify how neural networks learn, optimize parameters, make predictions, and process diverse data representations effectively.

---

# Contents

Each chapter is documented in **its own Jupyter Notebook** and includes:

- Chapter summary.
- Learning objectives.
- Theoretical explanation of important concepts.
- Code reproduction based on the book or official repository.
- Detailed code explanation.
- Result analysis and interpretation.
- Discussion and conclusion.

The learning progression follows the 16 chapters of the book and covers the following topics:

Fundamental Concepts of Deep Learning: Machine learning principles, supervised and unsupervised learning, and parametric and nonparametric models.

Neural Prediction and Forward Propagation: Building simple neural networks to generate predictions from input data.

Gradient Descent and Neural Learning: Understanding prediction errors, weight updates, learning rates, and parameter optimization.

Multiple Weights and Deep Neural Networks: Extending neural networks to multiple inputs and outputs, matrix operations, and backpropagation.

Neural Network Visualization: Developing intuitive representations of network architectures and their computational relationships.

Regularization and Generalization: Exploring overfitting, early stopping, dropout, and batch gradient descent.

Activation Functions and Probability Modeling: Understanding nonlinear transformations, hidden-layer activations, and output probabilities.

Convolutional Neural Networks (CNNs): Learning how shared weights and convolutional layers identify patterns in structured data.

Natural Language Processing (NLP): Exploring sentiment classification, word embeddings, semantic relationships, and word analogies.

Recurrent Neural Networks (RNNs): Processing variable-length sequences and learning relationships between words and other sequential data.

Automatic Differentiation and Deep Learning Frameworks: Implementing tensors, automatic gradient computation, optimization, and neural network layers from scratch.

Long Short-Term Memory (LSTM): Understanding recurrent learning, character-level language modeling, and the challenges of vanishing and exploding gradients.

Federated Learning and Data Privacy: Exploring decentralized model training, secure aggregation, and homomorphic encryption.

Further Learning and Practical Development: Identifying resources and strategies for continuing the study of deep learning.

--- 

# Repository Structure

The repository is organized with all chapter notebooks directly in the root directory, while datasets are maintained in a dedicated folder.

Grokking-Deep-Learning/
│
├── datasets/
│   ├── en/
│   ├── shuffled/
│   ├── ham.txt
│   ├── labels.txt
│   ├── reviews.txt
│   ├── shakespeare.txt
│   └── spam.txt
│
├── Chapter01_Introducing_Deep_Learning.ipynb
├── Chapter02_Fundamental_Concepts.ipynb
├── Chapter03_Introduction_to_Neural_Prediction.ipynb
├── Chapter04_Introduction_to_Neural_Learning.ipynb
├── Chapter05_Learning_Multiple_Weights.ipynb
├── Chapter06_Building_Your_First_Deep_Neural_Network.ipynb
├── Chapter07_How_to_Picture_Neural_Networks.ipynb
├── Chapter08_Learning_Signal_and_Ignoring_Noise.ipynb
├── Chapter09_Modeling_Probabilities_and_Nonlinearities.ipynb
├── Chapter10_Neural_Learning_about_Edges_and_Corners.ipynb
├── Chapter11_Neural_Networks_that_Understand_Language.ipynb
├── Chapter12_Neural_Networks_that_Write_Like_Shakespeare.ipynb
├── Chapter13_Introducing_Automatic_Optimization.ipynb
├── Chapter14_Learning_to_Write_Like_Shakespeare.ipynb
├── Chapter15_Deep_Learning_on_Unseen_Data.ipynb
├── Chapter16_Where_to_Go_from_Here.ipynb
│
├── .gitignore
└── README.md

***Note:*** *The notebook filenames above follow the book's chapter titles. If any filename in your existing repository differs, update the corresponding entry to match the actual filename.*

--- 

Tools & Libraries

The project uses the following tools and technologies:

- Python 3.x
- Jupyter Notebook
- Visual Studio Code
- NumPy
- Git and GitHub

Python and NumPy support the implementation of neural network operations, matrix computations, gradient descent, and other numerical procedures. Jupyter Notebooks provide an interactive environment for combining theoretical explanations, executable code, and result analysis.

The implementation approach emphasizes understanding the underlying mechanics of deep learning rather than relying exclusively on high-level machine learning frameworks.

--- 

# Learning Purpose

This repository is developed as part of the **Deep Learning** course at **Telkom University**.

The primary objective is to develop a systematic understanding of deep learning through theoretical study, code reproduction, and practical experimentation.

By implementing neural networks and examining their computational processes, this project explores how models learn patterns, adjust weights, minimize prediction errors, and generalize to unseen data.

The repository also provides an opportunity to study more advanced architectures, including convolutional neural networks, recurrent neural networks, and long short-term memory networks, alongside emerging approaches to privacy-preserving machine learning.

Ultimately, this project serves as both an academic assignment and a personal learning reference for understanding the principles and practical applications of deep learning.

---

# Usage Notes

GitHub renders Jupyter Notebooks directly in the browser, although the reading experience may vary depending on the complexity of the notebook and its outputs.

For a more complete learning experience, it is recommended to open the notebooks locally using Visual Studio Code or Jupyter Notebook, where code cells can be executed and modified interactively.

Before running a notebook, ensure that Python and the required libraries are installed and that dataset paths are consistent with the repository structure.

---

# Reference

Trask, A. W. (2019). 
*Grokking Deep Learning.* Manning Publications.

Original code repository:
https://github.com/iamtrask/grokking-deep-learning

Publisher's book page:
https://www.manning.com/books/grokking-deep-learning

---

<p align="center">
  <i>Created by <b>kinanpta</b></i>
</p>