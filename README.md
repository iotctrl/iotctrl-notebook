# Control Systems Simulation Notebooks

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/iotctrl/iotctrl-notebook/HEAD?filepath=simulation.ipynb)

This repository hosts Jupyter notebooks for simulating control systems part of the IoTControl framework, using the `python-control` library.  
**Run instantly** in your browser via Binder—no local installation required!

## 🚀 Quick Start
1. **Click the "Launch Binder" button above** (may take 2-5 minutes to build the first time).
2. Open a notebook (e.g., `simulation.ipynb`) in JupyterLab.
3. Run cells to execute simulations/plots.

## 📦 Pre-installed Packages
The Binder environment includes:
- `python-control` (with full `scipy`/`numpy` support)
- `matplotlib` (for plotting)
- `jupyterlab` (interactive IDE)

## 🔧 Customize Simulations
1. **Edit notebooks locally**: Install dependencies first:
   ```bash
   conda env create -f environment.yml
   conda activate control-env
   jupyter lab
