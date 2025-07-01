# 📈 Evolution of Dark Energy Parameters

This repository explores the **evolution of dark energy parameters** in a cosmological context. It focuses on numerically computing and visualizing:

* **Scale Factor** $a(t)$
* **Fractional Energy Densities** $\Omega_i(t)$ for matter and dark energy
* **Deceleration Parameter** $q(t)$
* **equation of state state w(t)

## 🧠 Overview

Understanding how dark energy evolves is critical to modern cosmology. This project investigates how various cosmological parameters behave over time, particularly in models involving scalar fields, quintessence, or ΛCDM baselines.

## 🧲 Model Description

Model Description

We solve the Friedmann equations numerically using Python. The evolution equations include:

The scale factor : describes the expansion of the universe.

The fractional energy density:



where .

The deceleration parameter:


These equations are solved using numerical integration (`scipy.integrate.solve_ivp`), and results are visualized using `matplotlib`.



## 📊 Results

Example outputs:

* ✅ Plot of scale factor $a(t)$
* ✅ Evolution of $\Omega_m(t)$, $\Omega_{\text{DE}}(t)$
* ✅ Deceleration parameter $q(t)$ showing acceleration transition


## 🧭 Future Work

* Extend to non-minimally coupled models
* Fit with observational data (SNe Ia, BAO)
* Include equation of state evolution $w(z)$

