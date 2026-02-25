# ARP as Gradient Flow in Adaptive-π Geometry

**ID:** `eq-arp-gradient-flow-bridge`  
**Tier:** derived  
**Score:** 66  
**Units:** OK  
**Theory:** PASS-WITH-ASSUMPTIONS  

## Equation

$$
\dot G_{ij}=\alpha_G\,|I_{ij}|-\mu_G\,G_{ij},\quad |I_{ij}|\propto \frac{\partial\sqrt{\mathcal{E}}}{\partial(\sqrt{\Omega_{ij}G_{ij}})}
$$

## Description

Bridge theorem: ARP reinforcement is proportional to edge energy contributions in a πₐ-weighted Dirichlet landscape. ARP is a 'lazy' gradient flow where Ω = π_a/π changes what counts as a short/cheap path. Prediction: increasing πₐ in a region re-routes the ARP backbone away, even under the same boundary forcing. 'πₐ sculpts geodesics; ARP discovers them.'

## Assumptions

- Network is connected; Kirchhoff potentials are well-defined per step.
- Ω_{ij} is sampled from the continuous π_a field at edge midpoints.
- Budget/normalization constraint forces edge competition (not all edges grow).

## Repository Structure

```
images/       # Visualizations, plots, diagrams
derivations/  # Step-by-step derivations and proofs
simulations/  # Computational models and code
data/         # Numerical data, experimental results
notes/        # Research notes and references
```

## Links

- [TopEquations Leaderboard](https://rdm3dc.github.io/TopEquations/leaderboard.html)
- [TopEquations Main Repo](https://github.com/RDM3DC/TopEquations)
- [Certificates](https://rdm3dc.github.io/TopEquations/certificates.html)

---
*Part of the [TopEquations](https://github.com/RDM3DC/TopEquations) project.*
