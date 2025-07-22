# CERN Open Data Analyses

This repository contains independent analysis projects based on proton-proton collision data from the CMS experiment, provided via the [CERN Open Data Portal](https://opendata.cern.ch/).

All analyses are performed using Python with `uproot`, `awkward-array`, and other scientific libraries. Each project is organized in its own folder and includes code, data (if small), and a report.

---

## Projects

### 🔬 [Z Boson Analysis](./Z-boson/)
A study of Z boson production via the dilepton (ℓ⁺ℓ⁻) decay channel using CMS collision data. Includes:

- Jupyter notebook for data selection and invariant mass reconstruction
- Plots showing Z peak and kinematic distributions
- Final report (PDF)

###  [Z_Boson_and_Jet Analysis](./Z_Boson+Jets/)
An analysis of jet kinematics such as transverse momentum (`pₜ`) and pseudorapidity (`η`). This study focuses on:

- Jet selection and cleaning
- Histogramming of jet variables
- Discussion of jet distributions in high-energy events

---

## ⚙️ Requirements

To run the notebooks, install the required packages:

```bash
pip install numpy matplotlib uproot awkward scipy
