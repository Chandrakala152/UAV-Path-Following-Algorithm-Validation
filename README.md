# UAV Path Following Algorithm Validation

## Overview

This repository contains an independent Python implementation and validation of the UAV path-following algorithms presented in the paper:

**P. B. Sujit, S. Saripalli, and J. B. Sousa, "An Evaluation of UAV Path Following Algorithms," Proceedings of the 2013 European Control Conference (ECC), Zürich, Switzerland, July 17–19, 2013.**

The objective of this project is to reproduce the published simulation results, validate the implemented algorithms against the reference paper, and compare their performance using quantitative error metrics.

---

## Implemented Algorithms

The following guidance algorithms have been implemented and validated:

- Carrot Chasing
- Nonlinear Guidance Law (NLGL)
- Pure Pursuit and LOS-based Path Following (PLOS)
- Vector Field Guidance
- Adaptive Linear Quadratic Regulator (Adaptive LQR)

Each implementation includes:
- Python source code
- Google Colab notebook
- Reproduced simulation outputs

---

## Performance Evaluation

The algorithms were evaluated using the following metrics:

- Mean Cross-Track Error (Mean XTE)
- Maximum Cross-Track Error (Max XTE)
- Root Mean Square Error (RMSE)
- Final Cross-Track Error
- Settling Time

These metrics were used to compare the tracking accuracy and convergence performance of each guidance algorithm.

---

## Repository Structure

```
UAV-Path-Following-Algorithm-Validation/
│
├── README.md
├── Carrot_Chasing/
├── NLGL/
├── PLOS/
├── Vector_Field/
├── Adaptive_LQR/
├── Error_Analysis/
└── Report/
```

---

## Software Requirements

- Python 3.x
- NumPy
- Pandas
- Matplotlib
- Google Colab (recommended)

Install the required packages using:

```bash
pip install numpy pandas matplotlib
```

---

## How to Run

1. Clone this repository:

```bash
git clone https://github.com/Chandrakala152/UAV-Path-Following-Algorithm-Validation.git
```

2. Open the desired Python script or Google Colab notebook.

3. Execute the notebook or script to reproduce the simulation results.

4. Run the scripts inside the **Error_Analysis** folder to generate:
   - Error metrics
   - Performance comparison table
   - Benchmark plots

---

## Validation Summary

The reproduced simulation results show close qualitative agreement with those reported in the reference paper. Minor variations are attributed to numerical integration methods, simulation timestep, floating-point precision, and implementation-specific assumptions. Overall, the implemented algorithms successfully reproduce the published guidance behavior and provide a reliable framework for comparative performance evaluation.

---

## Report

The complete validation report is available in the **Report** folder.

---

## Author

**Chandrakala Kotapati**

B.Tech Aerospace Engineering

Dayananda Sagar University

---

## Acknowledgements

This project was developed as part of an academic validation study. AI-assisted software tools, including ChatGPT (OpenAI), Google Gemini, Anthropic Claude, and OpenAI Codex, were used to assist with Python code debugging, documentation improvement, report organization, formatting, and programming support. All mathematical models, algorithm implementations, simulation results, validation analyses, and conclusions were independently reviewed and verified by the author against the reference paper.

---

## License

This repository is intended for academic and educational purposes only.
