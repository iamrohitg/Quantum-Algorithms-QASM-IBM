# Quantum Computing Algorithms with IBM QASM & Qiskit

This repository contains implementations of quantum computing algorithms, specifically Grover's and Shor's algorithms, utilizing IBM's QASM (Quantum Assembly Language) and Qiskit, a comprehensive open-source quantum computing framework.

## Table of Contents

- [Overview](#overview)
- [Algorithms](#algorithms)
- [Coding Environment](#coding-environment)
- [Getting Started](#getting-started)
- [Contributing](#contributing)
- [License](#license)

## Overview

Quantum computing is revolutionizing the field of computing by offering exponential speedups over classical algorithms for certain problems. This repository focuses on the implementation of two key quantum algorithms, Grover's and Shor's, which are fundamental to understanding the capabilities and potential of quantum computing.

## Algorithms

### Grover's Algorithm

Grover's algorithm is a quantum algorithm for unstructured search that finds the unique input to a black box function that produces a particular output value, using just O(√N) evaluations of the function, where N is the size of the function's domain. It is a cornerstone of quantum computing for its potential to solve NP-complete problems efficiently.

- [Wikipedia: Grover's Algorithm](https://en.wikipedia.org/wiki/Grover%27s_algorithm#Applications)

### Shor's Algorithm

Shor's algorithm is a quantum algorithm for integer factorization, which can factor large numbers exponentially faster than the best-known classical algorithms. It is a significant milestone in quantum computing for its potential to break RSA encryption.

- [IBM Quantum: Shor's Algorithm](https://quantum-computing.ibm.com/composer/docs/iqx/guide/shors-algorithm)

### Quantum Phase Estimation

Quantum phase estimation is a quantum algorithm used to estimate the phase corresponding to an eigenvalue of a given unitary operator. It is a fundamental algorithm in quantum computing and is used as a subroutine in other quantum algorithms.

- [Wikipedia: Quantum Phase Estimation Algorithm](https://en.wikipedia.org/wiki/Quantum_phase_estimation_algorithm)

## Coding Environment

The code for these algorithms is written in QASM and utilizes Qiskit for simulation and execution. QASM is a low-level language for quantum computing that allows for the direct manipulation of quantum circuits. Qiskit provides a high-level interface to quantum hardware and simulators, making it easier to develop and test quantum algorithms.

## Getting Started

To get started with the code, clone the repository and follow the instructions in the individual algorithm directories. Ensure you have the necessary Python environment and Qiskit installed.

## Contributing

Contributions to this repository are welcome. Please feel free to submit issues, feature requests, or pull requests.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
