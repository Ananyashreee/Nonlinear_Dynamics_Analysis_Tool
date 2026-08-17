# Nonlinear-Dynamics-Analysis-Tool
# 🌀 Nonlinear Dynamics Analysis Tool

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python)
![NumPy](https://img.shields.io/badge/NumPy-Data%20Processing-013243?logo=numpy)
![SciPy](https://img.shields.io/badge/SciPy-Scientific%20Computing-8CAA22?logo=scipy)

## 📌 Overview
The **Nonlinear Dynamics Analysis Tool** is a high-performance Python framework designed to isolate and analyze deterministic chaotic behavior in complex time series data. Built to handle highly non-linear datasets (such as hydrological or climate records), this tool automates phase space reconstruction and quantifies system predictability.

## 🚀 Key Features
* **Phase Space Reconstruction:** Automates optimal time-delay estimations to unfold time series data into its true multidimensional state space.
* **Rapid LLE Calculation:** Calculates the Largest Lyapunov Exponent (LLE) utilizing **Rosenstein’s algorithm**. Leverages **SciPy KD-Trees** for rapid nearest-neighbor searches, significantly reducing computational overhead.
* **Interactive Visualization:** Generates interactive 2D and 3D attractor models to visually trace chaotic trajectories and state transitions.

## 🛠️ Tech Stack
* **Language:** Python
* **Core Libraries:** `NumPy` (Vectorized numerical operations), `SciPy` (KD-Trees, signal processing)
* **Visualization:** `Matplotlib` / `Plotly` (for interactive 2D/3D plotting)


