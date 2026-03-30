# Quantum Error Correction: Shor vs Steane Codes

This repository contains Python simulations comparing Shor's 9-qubit code and Steane's 7-qubit code under depolarizing noise.

## Results
Steane's code outperforms Shor's code by approximately 2 times at all error rates. Steane's code uses 7 qubits while Shor's code uses 9 qubits per logical qubit.

## Requirements
- Python 3.8 or higher
- Qiskit
- NumPy
- Matplotlib

## How to Run
pip install qiskit numpy matplotlib

## References
- Shor, P. W. (1995). Scheme for reducing decoherence in quantum computer memory.
- Steane, A. M. (1996). Error correcting codes in quantum theory.
