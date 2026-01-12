# Circuit-QED Spin Dynamics Simulation Data

**Supplementary material for:**  
**[Analog Circuit-QED Simulator of Quantum Spin Dynamics Through the Extended Bose-Hubbard Model](https://arxiv.org/abs/2507.03587)**  
*arXiv:2507.03587 [quant-ph]*

[![arXiv](https://img.shields.io/badge/arXiv-2507.03587-b31b1b.svg)](https://arxiv.org/abs/2507.03587)

## 📁 Contents

This repository contains the numerical simulation data used to generate the figures in this paper.

### File Structure:
```
data/
├── Fig3/      # Data for Figure 3a: Magnetization flow for dimerizations \delta = (0,0.1,0.2,0.3)
               # Data for Figure 3b: Deviations of the local spin expectation values for different sites 
├── Fig4/      # Data for Figure 4:  Correlation function for different sites 
├── Fig5/      # Data for Figure 5:  Dynamics of the quantum Fisher information density for anisotropy parameters \eta = (0,0.1,0.2,0.3)
└── Fig6/      # Data for Figure 6:  Imbalance dynamics for disorder strengths W = (10, 50, 80, 100)
```

### Data Format:
Each `.npy` file is a NumPy dictionary containing:
- `time`: Time points array
- `observable_spin`: Spin observable values
- `observable_boson`: Boson observable values
- `dimerization`: Parameter value (where applicable)


## 📄 Citation

If you use this data, please cite:

```bibtex
@article{circuit_qed_spin_2024,
  title={Analog Circuit-QED Simulator of Quantum Spin Dynamics Through the Extended Bose-Hubbard Model},
  author={Authors},
  year={2024},
  eprint={2507.03587},
  archivePrefix={arXiv},
  primaryClass={quant-ph}
}
```

## 📜 License

The datasets are provided under the **Creative Commons Attribution 4.0 International (CC BY 4.0)** license.

---
