# Young's Double Slit Ultrasound Experiment

![Python](https://img.shields.io/badge/Python-3.10%2B-blue.svg)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)
![NumPy](https://img.shields.io/badge/NumPy-Acoustics-013243.svg)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-11557c.svg)

## Overview
Simulation of two coherent spherical ultrasound waves emitted on the left edge of a plane (at $x = 0$, separated by distance $d = 3.0\text{ mm}$) and propagating to the right in water ($c = 1480\text{ m/s}, f = 2.0\text{ MHz}, \lambda = 0.74\text{ mm}$).

### Visualizations
- **Real Part $\operatorname{Re}\{\psi(x, y)\}$**: Shows propagating wavefronts and phase interference.
- **Amplitude $|\psi(x, y)|$**: Shows constructive and destructive interference lobes.

![Wavefield](Youngs_double_slit_exp_Nachiketh_wavefield.png)

### Amplitude Profile at Distance $z = 30\text{ mm}$
At a sufficiently large distance $z$ ($z \gg d$), the amplitude profile is calculated analytically using the far-field Fraunhofer approximation / spatial Fourier transform:
$$|\psi_{\text{far}}(z, y)| \approx \frac{2}{z} \left| \cos\left( \frac{\pi d y}{\lambda z} \right) \right|$$

![Profile](Youngs_double_slit_exp_Nachiketh_profile.png)

## Repository Structure
- `Youngs_double_slit_exp_Nachiketh.ipynb`: Jupyter notebook containing the full simulation and plots.
- `Youngs_double_slit_exp_Nachiketh_wavefield.png` / `.pdf`: Wavefield Real Part & Amplitude plots.
- `Youngs_double_slit_exp_Nachiketh_profile.png` / `.pdf`: Profile comparison at distance $z = 30\text{ mm}$.
- `README.md`: Project summary.
