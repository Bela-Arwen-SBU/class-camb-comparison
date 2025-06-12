# CLASS vs CAMB: Comparative Analysis

This repository contains notebooks and scripts for comparing the outputs of CLASS (Cosmic Linear Anisotropy Solving System) and CAMB (Code for Anisotropies in the Microwave Background), the two most widely used Boltzmann codes in cosmology. The goal is to explore differences and similarities in their treatment of cosmological parameters, dark energy models, and resulting observables.

---

## Overview

- **Purpose:**  
  To provide clear, reproducible comparisons between CLASS and CAMB outputs for various cosmological scenarios, with a focus on dark energy and modified gravity models.

- **Approach:**  
  Python-based wrappers and Jupyter Notebooks are used to run both codes, process their outputs, and visualize results side-by-side.

---

## Features

- Run CLASS and CAMB with identical cosmological parameters.
- Generate and compare predictions for key observables (e.g., CMB power spectra, matter power spectra).
- Explore effects of altering dark energy/modified gravity parameters.
- Visualize differences with easy-to-edit plotting scripts.
- Modular structure for adding new models and parameter scans.

<!---

## Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Bela-Arwen-SBU/class-vs-camb.git
   cd class-vs-camb
   ```

2. **Install dependencies:**  
   Make sure you have Python 3.x and Jupyter installed.  
   Install required packages:
   ```bash
   pip install numpy matplotlib classy camb
   ```

   You’ll also need local installations of:
   - [CLASS](https://github.com/lesgourg/class_public) (for `classy` to work)
   - [CAMB](https://github.com/cmbant/CAMB) (for `camb` Python module)

3. **Run the main notebook:**
   ```bash
   jupyter notebook
   ```
   Open the main notebook (e.g., `compare_class_camb.ipynb`) to begin.

---

## Repository Structure

```
class-vs-camb/
│
├── notebooks/                # Jupyter notebooks for analysis and visualization
│   └── compare_class_camb.ipynb
├── data/                     # Example input/output data (if public)
├── scripts/                  # Python scripts for running CLASS/CAMB and parsing output
├── requirements.txt
├── LICENSE
├── CITATION.cff
└── README.md
```

---

## Example Plots

<!-- Optionally add example figures here when available -->
<!-- ![Sample Comparison Plot](notebooks/example_plot.png) -->

--->

## Citation

If you use this repository, please cite as:

```
Béla Arwen. (2025). CLASS vs CAMB: Comparative Analysis. GitHub. https://github.com/Bela-Arwen-SBU/class-vs-camb
```

Or see [CITATION.cff](./CITATION.cff) for more formats.

---

## License

This project is licensed under the MIT License. See [LICENSE](./LICENSE) for details.

---

## Contact

- **Béla Arwen** – bela.arwen@stonybrook.edu  
- [LinkedIn](https://www.linkedin.com/in/belaarwen/)

---

_Exploring the cosmos through precision and comparison._
