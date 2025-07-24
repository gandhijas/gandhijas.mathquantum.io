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

## Tools (Optional)
- Qiskit (IBM)
- Python (NumPy, Matplotlib)
- IBM Quantum Lab

Quantum Machine Learning (QML) relies on a mix of **quantum principles** and **mathematical tools** from linear algebra, probability, and optimization. These foundations allow quantum circuits to process and learn from data in ways that classical systems cannot.

---

## **Mathematical Foundations**

- **Qubits and Superposition:** A qubit is represented as  
  \[
  |\psi\rangle = \alpha |0\rangle + \beta |1\rangle,
  \quad |\alpha|^2 + |\beta|^2 = 1.
  \]  
  Qubits can exist in a superposition of states, unlike classical bits.

- **Quantum Gates:** Gates like **Hadamard (H)** and **Pauli-X (X)** are unitary matrices that transform qubits.  
  Example:  
  \[
  H = \frac{1}{\sqrt{2}} \begin{pmatrix} 1 & 1 \\ 1 & -1 \end{pmatrix}.
  \]

- **Measurement:** When measured, qubits collapse probabilistically to \(|0\rangle\) or \(|1\rangle\), with probabilities \(|\alpha|^2\) and \(|\beta|^2\).

- **Tensor Products:** Multi-qubit systems use tensor products to represent combined states, growing the state space exponentially.

- **Variational Circuits:** Hybrid algorithms use parameterized gates \(U(\theta)\) optimized by classical gradient-based methods to train quantum models.

---

## **Techniques in QML**
- **Quantum Feature Maps:** Encoding classical data into quantum states.  
- **Quantum Kernels:** Using quantum circuits to calculate similarity measures for classification tasks.  
- **Quantum Neural Networks (QNNs):** Parameterized circuits acting like neural layers, trained via hybrid optimization.

---

## **Tools**
- **Qiskit** (IBM) and **Pennylane** (Xanadu) for building quantum circuits.
- **NumPy & Python** for classical preprocessing.
- **Bloch Sphere** for visualizing qubit states and gates.

---

{: .notice--info}

