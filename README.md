# ⚛️ Python Quantum Circuit Simulator

A from-scratch computational engine that simulates a quantum computer using linear algebra. This project explores the mathematical framework of quantum gates and state-vector evolution without using high-level libraries like Qiskit.

## 🚀 Overview
I built this engine to better understand how quantum algorithms like **GHZ Entanglement** and **Quantum Teleportation** actually manipulate the probability amplitudes of a state vector in Hilbert space.

## 🛠️ Technical Features
* **Linear Algebra Engine:** Uses NumPy to perform Kronecker products ($\otimes$) for multi-qubit gate application.
* **Gate Library:** Includes implementations for Hadamard (H), Pauli-X, Y, Z, Phase (S), and T gates.
* **Controlled Logic:** Features a robust CNOT (CX) matrix generator that builds the correct $2^n \times 2^n$ operator for any control-target pair.
* **Custom Parser:** A lightweight string-based parser that lets you write "code" in a simplified QASM format and execute it on the simulator.



## 📊 Included Experiments
The simulator currently includes pre-configured scripts for:
1.  **GHZ State:** Creating maximum entanglement across 3 qubits ($|000\rangle + |111\rangle$).
2.  **Quantum Teleportation:** A partial simulation of the protocol used to transfer quantum information between qubits via entanglement.

## 💻 How to Run
Ensure you have NumPy installed:
```bash
pip install numpy
