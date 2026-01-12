# spin-dynamics-cQED-EBH-simulator
Supplementary material for "Analog Circuit-QED Simulator of Quantum Spin Dynamics Through the Extended Bose-Hubbard Model"


Вот минималистичный и правильный README для вашего случая:

---

# Circuit-QED Spin Dynamics Simulation Data

**Supplementary material for the paper:**  
**[Analog Circuit-QED Simulator of Quantum Spin Dynamics Through the Extended Bose-Hubbard Model](https://arxiv.org/abs/2507.03587)**  
*arXiv:2507.03587 [quant-ph]*

[![arXiv](https://img.shields.io/badge/arXiv-2507.03587-b31b1b.svg)](https://arxiv.org/abs/2507.03587)

## 📁 Contents

This repository contains the numerical simulation data used to generate the figures in the above paper.

### File Structure:
```
data/
├── Fig3/      # Data for Figure 3: Spin dynamics vs. dimerization
├── Fig4/      # Data for Figure 4: Parameter scans  
├── Fig5/      # Data for Figure 5: Analytical comparisons
└── Fig6/      # Data for Figure 6: Long-time correlations
```

### Data Format:
Each `.npy` file is a NumPy dictionary containing:
- `time`: Time points array
- `observable_spin`: Spin observable values
- `observable_boson`: Boson observable values
- `dimerization`: Parameter value (where applicable)

## 📊 How to Use

1. **Load data in Python:**
   ```python
   import numpy as np
   data = np.load('data/Fig3/dimerization_0.1.npy', allow_pickle=True).item()
   ```

2. **Reproduce figures:** The data can be plotted using standard matplotlib routines as described in the paper.

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

*This repository accompanies the preprint on arXiv. For questions, please contact the corresponding author.*

---

**Этот README:**
1. ✅ Ссылается на arXiv
2. ✅ Кратко описывает файлы
3. ✅ Показывает структуру данных
4. ✅ Дает пример загрузки
5. ✅ Включает шаблон для цитирования
6. ✅ Указывает лицензию

Просто скопируйте этот текст в файл `README.md` в вашем репозитории.
