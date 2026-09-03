# Shor's Algorithm: Factoring 15 and 21 with Full Circuit

**EMAAN ADAL | 0085533**

This repository contains the complete implementation and empirical analysis of integer factorization comparing classical benchmarking paradigms with Shor's quantum factoring algorithm. This project was developed as part of the **ELEC/PHYS 450/550: Quantum Computing** course at **Koç University** (Spring 2026).

## Project Overview

The project is structured into two main exploration domains within a unified Jupyter Notebook environment:
1. **Part 1 — Classical Approach**: Core benchmarking implementations of traditional factoring methodologies spanning Trial Division, Pollard's Rho, and a conceptual variation of the Quadratic Sieve across various parameter spaces ($N = 15$ to $10,403$).
2. **Part 2 — Quantum Approach**: Scaled construction and execution of Shor's period-finding quantum circuits designed explicitly for $N = 15$ and $N = 21$ using the Qiskit library ecosystem.

---
## Installation
pip install qiskit qiskit-aer numpy sympy matplotlib

## Directory Structure

```text
├── shors_algorithm_0085533.ipynb          # Main Python workspace notebook
├── README.md                      # Setup and execution manual (This file)
└── img                             # Generated figures (histograms, benchmarks, scaling plots)
```
## Environment Setup (Optional but Recommended)
---
### On macOS / Linux
python3 -m venv qenv

source qenv/bin/activate

### On Windows (Command Prompt)
python -m venv qenv

call qenv\Scripts\activate

## Running the Project
Step 1: Launch Jupyter Notebook
jupyter notebook

Open:
factorization_project.ipynb

From the notebook menu:

Kernel → Restart Kernel and Run All



