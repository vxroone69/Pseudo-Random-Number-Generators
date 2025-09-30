# Pseudo-Random Number Generators (PRNG) Comparison Tool

## Overview
This project implements and compares different Pseudo-Random Number Generators (PRNGs) based on their statistical and performance characteristics. The tool evaluates key metrics such as mean, standard deviation, chi-square, and entropy. The comparison helps in identifying which PRNGs are more suitable for simulations, cryptography, and other applications where randomness quality is crucial.

## Features
- Modular implementation of PRNGs in Python.
- Performance testing using execution time.
- Statistical analysis of generated random numbers.
- Uniformity checks using Chi-Square and Std-dev tests.
- Entropy measurement for unpredictability.

## Parameters Evaluated
- **Execution Time:** Speed of generation.
- **Mean:** Should be close to 0.5 for uniform distribution in [0,1].
- **Standard Deviation:** Should be close to 0.7223 for uniform [0,1].
- **Chi-Square Test:** Should be close to expected value (k–1, 255-1)
- **Entropy:** Higher entropy = better randomness.

## Requirements
- Python 3.8+
- Libraries: `numpy`, `scipy`, `time`, `matplotlib`

Install dependencies with:
```bash
pip install numpy scipy matplotlib

![Alt text](images/output.png)

