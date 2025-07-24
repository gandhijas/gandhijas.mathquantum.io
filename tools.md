---
layout: single
title: "Tools & Techniques"
permalink: /tools/
---

## Mathematics Areas
- Linear Algebra: unitary matrices and quantum state vectors.
- Probability: quantum measurement and outcomes.
- Optimization: variational quantum circuits.
- Complex Numbers: representation of qubit states.


Quantum Machine Learning (QML) relies on **quantum principles** and **mathematical tools** such as linear algebra, probability, and optimization.

---

## **Mathematical Foundations**

- **Qubits and Superposition:**  
  $$|\psi\rangle = \alpha |0\rangle + \beta |1\rangle,\ |\alpha|^2 + |\beta|^2 = 1.$$

- **Quantum Gates:** Gates like Hadamard (H) and Pauli-X (X) are unitary matrices that transform qubits:  
  $$
  H = \frac{1}{\sqrt{2}}
  \begin{pmatrix}
  1 & 1 \\
  1 & -1
  \end{pmatrix}.
  $$

- **Measurement:**  
  $$P(0) = |\alpha|^2,\ P(1) = |\beta|^2.$$

- **Tensor Products:** Multi-qubit systems use tensor products to represent combined states.

- **Variational Circuits:** Parameterized gates \(U(\theta)\) are optimized via classical gradient descent.

---

## **Techniques in QML**
- **Quantum Feature Maps** – encoding classical data into quantum states.
- **Quantum Kernels** – quantum-powered similarity measures for classification.
- **Quantum Neural Networks (QNNs)** – parameterized circuits trained via hybrid optimization.

---

## **Tools**
- **Qiskit** and **Pennylane** – quantum circuit simulation and design.
- **NumPy & Python** – classical data preprocessing.
- **Bloch Sphere** – qubit state visualization.

---

