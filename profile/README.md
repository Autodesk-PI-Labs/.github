# π-Labs: Physics Informed AI

Welcome to **π-Labs**, the **Physics Informed AI** research group within **Autodesk Research**. We build AI methods that respect the physics of the systems Autodesk customers design and make, from flow, acoustics and thermal effects to structures and urban environments. The plural is deliberate: the group is spread across multiple locations.

<p align="center">
    <img alt="π-Labs" src="../pi_labs_scheme.svg" width="1000" />
</p>

## About us 🏫

π-Labs is led by **Prof. Nathan Kutz** and is part of [Autodesk Research](https://www.research.autodesk.com/). Our work spans scientific machine learning, reduced order modelling, data assimilation, and geometry optimisation and generation, with the goal of putting physics directly in the design loop.

**Head of π-Labs**:

- Prof. Nathan Kutz (London)

**Leadership** (reporting to Nathan Kutz):

- Dr. Adrian Butscher (Toronto)
- Dr. Nigel Morris (Toronto)
- Dr. Massimiliano Meneghin (remote, Italy)

**London** (reporting to Nathan Kutz):

- Dr. Paolo Conti
- Dr. Elise Ozalp
- Dr. Stefano Riva

**Toronto** (reporting to Adrian Butscher):

- Dr. Adrian Humphry
- Dr. Hesam Salehipour
- Dr. Jenmy Zhang
- Dr. Mehran Ebrahimi

**Seattle** (reporting to Adrian Butscher):

- Dr. Jan Williams

## Research areas 🔍

### Scientific ML for dynamical systems 🌀
- **Objective:** Learn compact, interpretable and predictive models of spatio-temporal dynamics from data, combining reduced order modelling with machine learning for PDE-governed systems.

### Data assimilation and ML 📡
- **Objective:** Fuse sparse real-world measurements with simulation to reconstruct and forecast full physical states, closing the gap between simulation and reality.

### Topology and geometry optimisation 📐
- **Objective:** Optimise shapes and topologies against physics-based objectives in a computationally tractable way.

### Generative geometry with AI 🧬
- **Objective:** Generate and explore new geometries with generative models, with latent spaces that can be searched and optimised directly.

### Physics-informed geometry (PIG) 🐷
- **Objective:** In many multi-physics systems, the geometry induces the physics, and the physics is critical for optimising the geometry itself. We optimise geometry for physics-based performance, from building design to automotive aerodynamics.
- **Idea:** Both geometry and physics are very high-dimensional, so we optimise in low-rank latent spaces of each: $\mathbf{G}^* = \arg\min_{\mathbf{G}} \mathcal{L}(\mathbf{U})$ becomes a search over a latent geometry $\mathbf{g}$ with a reduced order model of the physics, then refined on the full model.
- **Directions:** PCA-parametrised and generative latent geometries, out-of-distribution robustness, and sim2real geometry assimilation from sparse sensors. Use cases include airfoils, audio speakers, urban flow and motorsport design.

## Contact us 📬

- **Web:** [Autodesk Research](https://www.research.autodesk.com/)
- **Locations:** London, Toronto, Seattle and remote

---

**Disclaimer:** The code developed by our group is intended for research purposes.

---
