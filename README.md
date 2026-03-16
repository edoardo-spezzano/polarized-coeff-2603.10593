# Appendix: Analytic Results for Polarized Massive Coefficient Functions

This repository provides a computer-readable implementation of the analytic results presented in the paper: ([Heavy-quark contributions to the polarized DIS
structure functions at NLO in the ACOT scheme](https://arxiv.org/pdf/2603.10593)). 

---

## 1. Polarized Gluon Fusion
**File:** `PolarizedGluonFusion.m`

### Description

This module implements the analytic expressions for the polarized gluon-initiated channel, as derived in Equation 4.16 of the main manuscript

---

## 2. Polarized Quark Scattering
**File:** `PolarizedQuarkScattering.m`

### Description
This module implements the quark-initiated scattering processes, providing both the fundamental soft, virtual and the integrated results. In particular, the coefficient sets $S_i, N_i \text{and} V_i$ are included. The module also contains the inclusive polarized quark-scattering functions, defined as

$$
\hat{g}_{i}^{\rm incl}(\hat{s}_1)=\int_{0}^{1} \hat{g}_{i}^{\text{QS}} (\hat{s}_1, \hat{t}_1 (y)) dy
$$


