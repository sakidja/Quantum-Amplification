# **Quantum_Amplification**
*Simulation of structured-bath quantum amplification in superconducting qubits.*

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sakidja/Quantum-Amplification/blob/main/Quantum_Amplification.ipynb)  
![Python Version](https://img.shields.io/badge/Python-3.x-blue.svg)  
![License](https://img.shields.io/badge/License-MIT-green.svg)

---

### 🧩 Overview
This repository contains the notebook **`Quantum_Amplification.ipynb`**, developed as part of the upcoming study *“Quantum Reciprocity: A Structured-Bath Hamiltonian for Coherent Amplification”* (Sakidja, 2025).  https://arxiv.org/abs/2510.17572
It extends the structured-bath framework to demonstrate coherent amplification in superconducting quantum bit devices.

---

### ⚙️ Model Description
The notebook implements a **six-node structured-bath Hamiltonian**, modeling a finite near-field environment coupled to a quantum system.  
By tuning inter-layer couplings, damping rates, and pump strength, the simulation captures transitions from passive response to active quantum amplification.  

This approach demonstrates how coherence can be preserved and even enhanced through engineered coupling — a principle central to *quantum reciprocity*.

---

### 🔍 Key Features
- Hamiltonian-based self-energy formulation (no reconstructive fitting).  
- Parameter sweeps over coupling strengths, damping, and pump drive.  
- Gain spectra and ridge-line plots visualizing coherence flow and amplification regimes.  
- Reproducible, modular workflow for exploring structured-bath architectures in quantum amplifiers.  

---

### 🚀 Usage
Run the notebook in any Python 3 environment (Jupyter or Colab) after installing dependencies:

```bash
pip install numpy scipy matplotlib
```

Execution will produce:  
- 2D gain and spectral maps  
- Ridge-line data showing peak amplification  
- Saved outputs in the **`/amplifier_data/`** directory  

Alternatively, open and run it directly in Google Colab by clicking the badge above or using this link:  
👉 [**Open Quantum_Amplification.ipynb in Colab**](https://colab.research.google.com/github/sakidja/Quantum-Amplification/blob/main/Quantum_Amplification.ipynb)

---

### 📁 Repository Structure
```
Quantum_Amplification/
│
├── Quantum_Amplification.ipynb   # Main simulation notebook
├── README.md                     # Project description
└── amplifier_data/               # Generated spectra, gain maps, and output files
```

---

### 📘 Notes
- The dataset and results correspond to amplifier configurations discussed in the upcoming manuscript submission.  
- This repository will be updated following the paper’s public release to include the formal citation and DOI.

---

### 📜 License
This project is distributed under the **MIT License**.  
You may freely use, modify, and distribute the code with acknowledgment of the original author.

