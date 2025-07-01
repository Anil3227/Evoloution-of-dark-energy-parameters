# Evoloution-of-dark-energy-parameters
This repository explores the evolution of dark energy parameters in a cosmological context. It focuses on numerically computing and visualizing:

Scale Factor 
a(t)

Fractional Energy Densities 
Ω
𝑖
(
𝑡
)
Ω 
i
​
 (t) for matter and dark energy

Deceleration Parameter 
𝑞
(
𝑡
)
q(t)

🧠 Overview
Understanding how dark energy evolves is critical to modern cosmology. This project investigates how various cosmological parameters behave over time, particularly in models involving scalar fields, quintessence, or ΛCDM baselines.

🧮 Model Description
We solve the Friedmann equations numerically using Python. The evolution equations include:

The scale factor 
𝑎
(
𝑡
)
a(t): describes the expansion of the universe.

The fractional energy density:

Ω
𝑖
(
𝑎
)
=
𝜌
𝑖
(
𝑎
)
𝜌
crit
(
𝑎
)
Ω 
i
​
 (a)= 
ρ 
crit
​
 (a)
ρ 
i
​
 (a)
​
 
where 
𝜌
crit
=
3
𝐻
2
8
𝜋
𝐺
ρ 
crit
​
 = 
8πG
3H 
2
 
​
 .

The deceleration parameter:

𝑞
(
𝑎
)
=
−
𝑎
¨
𝑎
𝑎
˙
2
=
−
1
−
𝐻
˙
𝐻
2
q(a)=− 
a
˙
  
2
 
a
¨
 a
​
 =−1− 
H 
2
 
H
˙
 
​
 
These equations are solved using numerical integration (scipy.integrate.solve_ivp), and results are visualized using matplotlib.
