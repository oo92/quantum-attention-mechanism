# README for Quantum Transformer Jupyter Notebook
## Overview
The *Quantum Transformer* Jupyter Notebook is a notebook designed to demonstrate quantum state encoding and the quantum attention mechanism. It integrates classical and quantum computing principles to enhance attention mechanisms.

## Features
*GPU Acceleration*: Utilizes GPU acceleration (Nvidia T4) for enhanced computational performance, particularly beneficial for quantum simulation tasks.

*Libraries and Dependencies*: qiskit, matplotlib, cuquantum, and cupy-cuda12x

*Quantum State Encoding*: Implements a function `amplitude_encode` to encode classical data vectors into quantum states using amplitude encoding, a technique crucial for preparing quantum states that represent classical information.

*Swap Test Implementation*: Provides a `swap_test function`, for estimating the similarity between two quantum states. This function is critical in quantum attention mechanisms, analogous to dot product calculations in classical attention systems.

*Quantum Measurement*: Includes a `measure_state` function for measuring the quantum state produced by the swap test and interpreting the results to derive attention scores.

*Classical Components Integration*: Contains classical implementations of Softmax and Weighted Sum functions.

By: Onur-Andros Ozbek
