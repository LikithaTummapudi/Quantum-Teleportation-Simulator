 # ⚛️ Quantum Teleportation using Qiskit

This project implements the quantum teleportation protocol using Qiskit. It transfers an unknown quantum state from Alice’s qubit to Bob’s qubit using entanglement and classical communication.

## 🛠️ Tools Used
Python

Qiskit

Qiskit Aer

NumPy

## 💻 How It Works
Initialize Circuit – Create a 3-qubit system

Unknown State – Generate a random state using a U gate

Entanglement – Create a Bell pair between qubits 1 and 2

Alice’s Operations – Apply CNOT + Hadamard, then measure

Bob’s Correction – Apply X and Z gates based on measurement results

Validation – Apply inverse U gate and measure to confirm teleportation

## 📊 Output 
Circuit diagrams

Bloch sphere visualizations

Final measurement verifying successful teleportation

## ✅ Conclusion

The project demonstrates how quantum states can be transmitted using entanglement without physically sending the qubit.
