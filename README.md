# Modelling Attosecond Electron Dynamics in Graphene  
### A Conceptual Proof-of-Concept Inspired by Early Neural Activity

**Author:** LAKSHITA  
**Status:** Independent research project (Gap Year, Post–Class 12)  
**Field:** Ultrafast condensed matter physics • Computational modeling • Conceptual neuro-inspired analogies

---

## Overview

This repository presents a **computational proof-of-concept** exploring whether **attosecond–femtosecond electron dynamics in graphene** can conceptually resemble the earliest stages of neural signal activity.

Using a **Dirac-like Hamiltonian near the K-point** and **Gaussian wavepacket excitation**, we simulate ultrafast electron oscillations under femtosecond-scale perturbations and analyze their coherence, decay, and interference patterns.

**Important:**  
This work is **conceptual and analogical**. It is **not** a biological simulation and does **not** include ion channels, membranes, or actual neural mechanisms.

---

## Methods (Summary)

* **Hamiltonian:** Dirac-like Hamiltonian for graphene near the K-point  
* **Initial State:** Gaussian electron wavepacket  
* **Excitation:** Femtosecond pulse (~2.5 eV)  
* **Time Evolution:** Time-dependent Schrödinger equation  
* **Numerical Method:** Split-operator Fourier method  
* **Time Step:** 0.1 fs  
* **Spatial Domain:** 10 nm × 10 nm (periodic boundaries)  
* **Outputs:** Heatmaps of electron density (|Ψ|²), time-dependent oscillation curves, coherence decay

---

## Figures

**Figure 1:** Electron density heatmap |Ψ|² after excitation (~10 fs)  
**Figure 2:** Normalized oscillation amplitude over time, showing exponential decay with characteristic coherence τ ≈ 15 fs  
**Figure 3 (optional):** Conceptual analogy comparing graphene oscillations to early neural activity  

> Only **representative figures** are included. Additional exploratory figures can be found in the `Extras` folder (if included).

---

## Interpretation & Scope

The observed rapid excitation, oscillatory response, and transient coherence are **structurally reminiscent** of early neural signal dynamics, despite operating on vastly different timescales.

This repository is intended to:

* Demonstrate the feasibility of ultrafast coherent modeling  
* Encourage interdisciplinary thinking  
* Serve as a foundation for future, more rigorous work

---

## Personal Reflection / Learning Journey

This project was developed independently during my **gap year** to explore physics-based modeling and interdisciplinary scientific thinking. It helped me learn how scientists:

* Turn equations into simulations  
* Visualize results through heatmaps and temporal plots  
* Interpret coherent dynamics conceptually  
* Compare physical systems to biological analogs in a meaningful way

This is **not a neural model**, but a learning-driven exploration to strengthen coding, visualization, and critical thinking skills.

---

## Limitations

* This is **not a biological simulation**  
* Ion channels, membranes, and other neural mechanisms are not modeled  
* Many-body electron interactions in graphene are ignored  
* Parameters are chosen for learning and visualization, **not experimental accuracy**  
* No comparison to real experimental data

---

## Next Steps / Future Learning

* Study spiking neuron models (Hodgkin–Huxley, Izhikevich)  
* Explore electrophysiology experiments and real neural datasets  
* Connect computational models to biological measurements  
* Investigate how biological systems maintain reliable signaling despite noise and energy constraints

---

## Citation & Use

If you use ideas, code, or figures from this repository, **please credit the author** by linking this GitHub repository.

This project may later be developed into a **formal preprint or academic manuscript**.

---

## Disclaimer

* No experimental validation claimed  
* All results are **conceptual** and intended for learning  
* Figures and code are **representative, not exhaustive**
