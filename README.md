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
│   ├── Magnetization flow for dimerizations δ = (0, 0.1, 0.2, 0.3)
│   └── Deviations of local spin expectation values for different sites
├── Fig4/      # Data for Figure 4
│   └── Correlation function for different sites
├── Fig5/      # Data for Figure 5
│   └── Dynamics of quantum Fisher information density 
│       for anisotropy parameters η = (0, 0.1, 0.2, 0.3)
└── Fig6/      # Data for Figure 6
    └── Imbalance dynamics for disorder strengths W = (10, 50, 80, 100)
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
