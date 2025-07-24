---
title: "Tools & Techniques"
layout: single
permalink: /tools/
---

Quantum Machine Learning (QML) combines quantum mechanics with classical machine learning principles. It uses quantum circuits as models for encoding data, finding patterns, and performing optimizations.

---

## **Mathematical Foundations**

- **Qubits and Superposition:**  
  $$|\psi\rangle = \alpha |0\rangle + \beta |1\rangle,\ |\alpha|^2 + |\beta|^2 = 1.$$

- **Quantum Gates:** Quantum gates, such as the **Hadamard** or **Pauli-X**, are unitary matrices that transform quantum states:  
  $$
  H = \frac{1}{\sqrt{2}}
  \begin{pmatrix}
  1 & 1 \\
  1 & -1
  \end{pmatrix}.
  $$

- **Measurement:**  
  $$P(0) = |\alpha|^2,\ P(1) = |\beta|^2.$$

- **Variational Circuits:** Parameterized quantum circuits \( U(\theta) \) act like trainable layers in neural networks, optimized with classical gradient-based algorithms to minimize a cost function.

---

## **Quantum Machine Learning Techniques**

1. Quantum Feature Maps  
Classical data (x) can be embedded into a quantum state (|ϕ(x)⟩) using a unitary transformation (U(x)).  
These embeddings allow quantum computers to calculate inner products (kernels) faster, useful for classification problems like those solved by classical SVMs.

2. Quantum Kernels  
A quantum kernel computes:  
\[ K(x, x') = |\langle ϕ(x) | ϕ(x') \rangle|^2 \]  
which measures similarity between data points in a high-dimensional Hilbert space—a concept similar to kernel methods in classical machine learning.

3. Variational Quantum Classifiers (VQCs)  
Variational circuits (U(θ)) act as quantum analogs to neural networks.  
The parameters (θ) are optimized using hybrid quantum-classical loops.


### **4. Quantum Approximate Optimization Algorithm (QAOA)**
QAOA can be adapted for **combinatorial optimization** tasks that appear in machine learning (like feature selection or clustering).

---

## **Tools**
- **Qiskit** and **Pennylane** – for building and simulating QML models.
- **NumPy & Python** – for classical preprocessing and hybrid training loops.
- **Bloch Sphere Visualization** – for understanding single-qubit operations.

---


