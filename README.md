# Evoloution-of-dark-energy-parameters
# 📈 Evolution of Dark Energy Parameters

This repository explores the **evolution of dark energy parameters** in a cosmological context. It focuses on numerically computing and visualizing:

* **Scale Factor** $a(t)$
* **Fractional Energy Densities** $\Omega_i(t)$ for matter and dark energy
* **Deceleration Parameter** $q(t)$

## 🧠 Overview

Understanding how dark energy evolves is critical to modern cosmology. This project investigates how various cosmological parameters behave over time, particularly in models involving scalar fields, quintessence, or ΛCDM baselines.

## 🧲 Model Description

We solve the Friedmann equations numerically using Python. The evolution equations include:

* The **scale factor** $a(t)$: describes the expansion of the universe.
* The **fractional energy density**:

  $$
  \Omega_i(a) = \frac{\rho_i(a)}{\rho_{\text{crit}}(a)}
  $$

  where $\rho_{\text{crit}} = \frac{3H^2}{8\pi G}$.
* The **deceleration parameter**:

  $$
  q(a) = -\frac{\ddot{a} a}{\dot{a}^2} = -1 - \frac{\dot{H}}{H^2}
  $$

These equations are solved using numerical integration (`scipy.integrate.solve_ivp`), and results are visualized using `matplotlib`.

## 📂 Repository Structure

```
├── main.py                 # Main simulation script
├── plots/                 # Output plots for a(t), Omega, q(t)
├── models/                # Potential functions or EoS models
├── utils/                 # Utility functions (e.g., numerical solvers)
└── README.md              # Project documentation
```

## 📊 Results

Example outputs:

* ✅ Plot of scale factor $a(t)$
* ✅ Evolution of $\Omega_m(t)$, $\Omega_{\text{DE}}(t)$
* ✅ Deceleration parameter $q(t)$ showing acceleration transition

![a(t) Plot](plots/scale_factor.png)
![Fractional Energy Density](plots/fractional_densities.png)
![Deceleration Parameter](plots/deceleration_parameter.png)

## 🚀 How to Run

1. Install required libraries:

   ```bash
   pip install numpy scipy matplotlib
   ```

2. Run the main script:

   ```bash
   python main.py
   ```

3. Plots will be saved in the `plots/` directory.

## 📚 References

* Planck 2018 results
* DESI 2025 BAO and Supernova data (optional if applicable)
* Copeland, Sami & Tsujikawa (2006) – *Dynamics of Dark Energy*

## 🧭 Future Work

* Extend to non-minimally coupled models
* Fit with observational data (SNe Ia, BAO)
* Include equation of state evolution $w(z)$

