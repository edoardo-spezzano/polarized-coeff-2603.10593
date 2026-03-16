# Appendix: Analytic Results for Polarized Massive Coefficient Functions

This repository contains the digital appendix and computer-readable implementation of the analytic results presented in the paper ([arXiv:2603.10593](https://arxiv.org/abs/2603.10593)). 

---

## 1. Polarized Gluon Fusion
**File:** `PolarizedGluonFusion.m`

### Description
This module implements the analytic expressions for the polarized gluon-initiated channel.

* **Analytic Content:** The file provides the full implementation of **Equation 4.16** as derived in the main text of the manuscript.

---

## 2. Polarized Quark Scattering
**File:** `PolarizedQuarkScattering.m`

### Description
This module focuses on the quark-initiated scattering processes ($q + \gamma^* \to Q + \bar{Q} + q'$), providing both the fundamental coefficients and the integrated results.

### A. Coefficient Sets ($S_i, N_i, V_i$)

### B. Inclusive Functions
For practical applications in PDF fits, this module includes the **inclusive polarized quark scattering functions**. These results are obtained by performing the analytic integration over the phase-space variable $y$:

$$\hat{g}_{i, \text{incl}}^{\text{QS}} (\hat{s}_1, \hat{t}_1) = \int_{0}^{1} \hat{g}_{i}^{\text{QS}} (\hat{s}_1, \hat{t}_1, y) \, dy$$

This integration allows for a direct mapping between the partonic results and the observable structure functions.


