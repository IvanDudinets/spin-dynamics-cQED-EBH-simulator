# Circuit-QED Spin Dynamics Simulation Data

**Supplementary material for:**  
**[Analog Circuit-QED Simulator of Quantum Spin Dynamics Through the Extended Bose-Hubbard Model](https://arxiv.org/abs/2507.03587)**  
*arXiv:2507.03587 [quant-ph]*

[![arXiv](https://img.shields.io/badge/arXiv-2507.03587-b31b1b.svg)](https://arxiv.org/abs/2507.03587)

## 📁 Contents

This repository contains the numerical simulation data used to generate all figures in the paper.

### File Structure:
```
data/
├── Fig3/      # Data for Figure 3
│   ├── dimerization_0.npy      # δ = 0.0
│   ├── dimerization_0p1.npy    # δ = 0.1
│   ├── dimerization_0p2.npy    # δ = 0.2
│   ├── dimerization_0p3.npy    # δ = 0.3
│   └── mj.npy                  # Local magnetization data
│   # Magnetization flow for dimerizations δ = (0, 0.1, 0.2, 0.3)
│   # Deviations of local spin expectation values for different sites
│
├── Fig4/      # Data for Figure 4
│   └── Cj.npy                  # Correlation function data
│
├── Fig5/      # Data for Figure 5
│   ├── anisotropy_0.npy        # η = 0.0
│   ├── anisotropy_0p1.npy      # η = 0.1
│   ├── anisotropy_0p2.npy      # η = 0.2
│   └── anisotropy_0p3.npy      # η = 0.3
│   # Dynamics of quantum Fisher information density
│   # for anisotropy parameters η = (0, 0.1, 0.2, 0.3)
│
└── Fig6/      # Data for Figure 6
    ├── W_10.npy                # W = 10
    ├── W_50.npy                # W = 50
    ├── W_80.npy                # W = 80
    └── W_100.npy               # W = 100
    # Imbalance dynamics for disorder strengths W = (10, 50, 80, 100)
```

### Data Format:
Each `.npy` file contains a NumPy dictionary with keys:
- `time`: Time points array
- `observable_spin`: Spin observable values  
- `observable_boson`: Boson observable values
- `dimerization` (where applicable): Dimerization parameter δ
- `anisotropy` (where applicable): Anisotropy parameter η
- `disorder` (where applicable): Disorder strength W


## 📄 Citation

If use this data, please cite the paper:

```bibtex
@article{circuit_qed_spin_2024,
  title={Analog Circuit-QED Simulator of Quantum Spin Dynamics Through the Extended Bose-Hubbard Model},
  author={Author List},
  year={2024},
  eprint={2507.03587},
  archivePrefix={arXiv},
  primaryClass={quant-ph}
}
```

## 📜 License

The simulation datasets are licensed under the **Creative Commons Attribution 4.0 International (CC BY 4.0)** license.

---

*For questions regarding this dataset, please contact the corresponding author.*

---
