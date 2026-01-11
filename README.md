# Euler-Modified-Euler-Heun-Methods
# Numerical Solutions to ODEs: Euler & Heun Methods

![Language](https://img.shields.io/badge/language-C%2B%2B-blue.svg)
![Course](https://img.shields.io/badge/Course-CSE261-green)

This repository contains a robust C++ implementation of numerical methods for solving Ordinary Differential Equations (ODEs). It was developed as part of the **Group C1** assignment for the Numerical Analysis course.

The project solves test ODEs, compares numerical approximations with exact analytical solutions, and generates error analysis plots.

## 📋 Table of Contents
- [Implemented Methods](#-implemented-methods)
- [Project Structure](#-project-structure)
- [Mathematical Formulation](#-mathematical-formulation)
- [Build & Run Instructions](#-build--run-instructions)
- [Results & Visualization](#-results--visualization)
- [Group Members](#-group-members)

## 🚀 Implemented Methods
We have implemented three primary single-step methods:
1.  **Euler's Method** (First-order accuracy)
2.  **Heun's Method** (Modified Euler / Predictor-Corrector)
3.  **Midpoint Method** (Runge-Kutta 2nd Order)

## 📂 Project Structure
```text
Numerical-ODE-Solver-CPP/
├── src/
│   ├── main.cpp          # Entry point and test configuration
│   ├── ODESolver.cpp     # Implementation of numerical algorithms
│   └── ODESolver.h       # Header file (Class definition)
├── data/                 # Generated CSV files containing simulation results
├── plots/                # Python-generated graphs (PNG)
├── tools/
│   └── plot_results.py   # Python script for data visualization
├── docs/                 # Assignment requirements and LaTeX reports
└── README.md             # Project Documentation
```
## 👥 Team & Collaboration

This project is a **group assignment** developed collaboratively by **Group C1** as part of the *Numerical Analysis (CSE261)* course.  
The team consists of **10 members**, who worked together on mathematical analysis, C++ implementation, testing, and documentation.

### 👤 Group Members
1. **Tarek Hossian** — ID: 2024100000382    
2. **Nura Nusrat Jannat** — ID: 2024000000320  
3. **Pritom Chowdhury** — ID: 2024000000007  
4. **Muntaha Hasnat Prionty** — ID: 2024000000033  
5. **Mesbah Uddin Molla** — ID: 2024000000105  
6. **Sumaiya Akter Mim** — ID: 2024100000265  
7. **Asifur Rahman Asif** — ID: 2024000000330  
8. **Riyad Uz Zaman** — ID: 2024000000231
9. **Tawfiq Al Ibad** — ID: 2024000000068  
10. **Mahjabeen Tur** — ID: 2024200000319  
