# 📈 Evolution of Dark Energy Parameters

This repository explores the **evolution of dark energy parameters** in a cosmological context. It focuses on numerically computing and visualizing:

* **Scale Factor** `a(t)`
* **Fractional Energy Densities** `Ωᵢ(t)` for matter and dark energy
* **Deceleration Parameter** `q(t)`
* ****Equation of state w(t)**

## 🧠 Overview

Understanding how dark energy evolves is critical to modern cosmology. This project investigates how various cosmological parameters behave over time, particularly in models involving scalar fields, quintessence, or ΛCDM baselines.

## 🧲 Model Description

We solve the Friedmann equations numerically using Python. The evolution equations include:

* The **scale factor** `a(t)`: describes the expansion of the universe.
* The **fractional energy density**:

  ```
  Ωᵢ(a) = ρᵢ(a) / ρ_crit(a)
  ```

  where:

  ```
  ρ_crit = 3H² / (8πG)
  ```
* The **deceleration parameter**:

  ```
  q(a) = - (ä a) / ȧ² = -1 - (Ḣ / H²)
  ```

These equations are solved using numerical integration (`scipy.integrate.solve_ivp`), and results are visualized using `matplotlib`.



Example outputs:

* ✅ Plot of scale factor `a(t)`
* ✅ Evolution of `Ω_m(t)`, `Ω_DE(t)`
* ✅ Deceleration parameter `q(t)` showing acceleration transition
* ✅  Equation of state 'w(t)'



## 🧭 Future Work

* Extend to non-minimally coupled models
* Fit with observational data (SNe Ia, BAO)
* Include equation of state evolution `w(z)`
