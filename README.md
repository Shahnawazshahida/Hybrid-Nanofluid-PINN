This repository contains a Physics-Informed Neural Network (PINN) implementation to solve the similarity boundary layer equations for mixed convection flow in hybrid nanofluids (Al₂O₃–Cu/water) with melting heat transfer effects.

## 📌 Features

- **Hybrid Nanofluid Model**
  Uses effective properties for Al₂O₃–Cu/water mixtures.

- **Physics-Informed Constraints**
  Solves coupled nonlinear ODEs for velocity $f(\eta)$ and temperature $\theta(\eta)$.

- **Adaptive Loss Weighting**
  Automatically balances physics and boundary-condition losses using gradient norms.

- **Uncertainty Quantification (UQ)**
  Includes ensemble training to verify PINN solution stability for $C_f$ and $Nu_x$.

- **Parameter Sweep**
  Generates $C_f(\lambda, M)$ and $Nu_x(\lambda, M)$ curves for various mixed-convection ($\lambda$) and melting ($M$) parameters.

---

## 🛠️ Installation & Requirements

1. **Clone the repository**

git clone [https://github.com/Shahnawazshahida/Hybrid-Nanofluid-PINN.git](https://github.com/Shahnawazshahida/Hybrid-Nanofluid-PINN.git)
