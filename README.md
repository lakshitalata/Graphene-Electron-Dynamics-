**Physics-Inspired Computational Exploration of Signal Dynamics and Conceptual Parallels to Neural Activity**

1) **What This Project Is**:-

This is an independent, self-directed computational project I developed on my personal laptop to learn how physical systems respond to excitation, evolve over time, and lose coherence — and to reflect on how those same ideas appear, in very different ways, in biological neural signaling.
This is not a biological model and not a peer-reviewed research paper. It is a learning-driven exploration that helped me build skills in physics-based modeling, numerical simulation, and interdisciplinary scientific thinking as preparation for undergraduate study in biology and physics.

2) **Why I Started This**:-

I’m interested in biology as a study of how living systems process information. Neurons transmit signals, respond to stimuli, and lose signal strength over time — but they do so using slow, energy-consuming biological mechanisms rather than fast, coherent physical ones.
To better understand what “signal dynamics” really means at a fundamental level, I decided to start with a simple, well-defined physical system: electrons in graphene near the Dirac point. This allowed me to focus on how excitation, oscillation, and decay emerge from mathematical models before thinking about how much more complex biological systems are.
This project was my way of learning how scientists turn equations into simulations, and simulations into interpretations.

3) **Where and How This Was Done**:- 
All work was done independently on my personal laptop. There was no physical lab or experimental setup.
My workflow was:
a) Studying background material from quantum mechanics, solid-state physics, and computational neuroscience textbooks and review papers
b)Writing simulation code in Python
c)Running numerical experiments locally
d)Visualizing results using plotted heatmaps and decay curves
e)Keeping written notes on what confused me, what worked, and what I would improve

This repository documents both the technical output and my learning process.

4) **What I Actually Modeled**:-
**Physical System**
I modeled electrons in graphene near the Dirac (K) point using a simplified Dirac Hamiltonian. This is a standard way to describe how electrons behave like relativistic particles in graphene.

**Initial State**
I represented the electron as a Gaussian wavepacket, which means I started with a localized “packet” of probability rather than a single point.

**Excitation**
I simulated the effect of a short, high-energy femtosecond-scale pulse to disturb the system and observe how the wavepacket evolved afterward.

**Time Evolution**
I numerically solved the time-dependent Schrödinger equation using a split-operator Fourier method. This allowed me to step the system forward in very small time increments (fractions of a femtosecond) and observe how the wavefunction changed.

5) **What I Measured and Visualized**:-
1. Electron Density Heatmaps:-
I generated 2D heatmaps of the wavefunction magnitude (|ψ|²) to see how the electron probability distribution spread and formed interference-like patterns over time.

2. Coherence Decay:-
I tracked how the oscillation strength changed over time and fit the results to an exponential decay curve. This gave a characteristic coherence timescale of around 15 femtoseconds.

6) **What This Taught Me About Biology**
This project made one thing very clear to me:
*Physical systems and biological systems operate on completely different kinds of time, energy, and mechanisms.*

In graphene, coherence disappears extremely fast because the system is governed by quantum dynamics. In neurons, signals persist because they are maintained by membranes, ion channels, and active biological processes that consume energy.

This contrast is what pushed me toward biology. I want to understand how living systems achieve reliable communication using slow, noisy, physical components — and how that differs fundamentally from the clean, mathematical systems we model in physics.

7) **Limitations**
a) This is not a neural model
b) No ion channels, membranes, or biological mechanisms are included
c) Many-body electron interactions in graphene are ignored
d) Parameters are chosen for learning and visualization, not experimental accuracy
e) There is no comparison to real experimental data

This project is meant as a learning and exploration tool, not a scientific claim.

8) **What I Want to Learn Next**

a)Spiking neuron models (Hodgkin–Huxley, Izhikevich)
b)How electrophysiology experiments generate real neural data
c)How computational models connect biological measurements to physical principles
d)How biological systems maintain signal reliability despite noise and energy constraints
