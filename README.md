# Quantum Random Number Generator

This project implements a **Quantum Random Number Generator (QRNG)** using Qiskit's quantum computing framework. The quantum circuit utilizes **Hadamard gates** to create superposition and measures the qubits to generate a truly random number.

## How It Works
1. **Create a Quantum Circuit** with 4 qubits and 4 classical bits.
2. **Apply Hadamard Gates** to put each qubit into superposition.
3. **Measure the Qubits** to collapse them into a random binary state.
4. **Simulate the Circuit** using Qiskit's `AerSimulator`.
5. **Extract a Random Outcome** from the measurement results and convert it to a decimal number.

## Dependencies
- Qiskit
- Matplotlib
- Python 3.x

# Visualization
The script also generates a histogram of the measurement results.
