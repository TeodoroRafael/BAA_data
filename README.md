# Bone Age Assessment Dataset

Dataset for **Bone Age Assessment** using **Greulich and Pyle** metrics.

## Citation

If you use this dataset in your research or project, please cite the following paper:

> Teodoro, R. do A., de Lima, F. V., Popa, M., Sampaio, G. S., Kochi, C., Longui, C. A., & da Silva, L. A. (2026). *Automatic bone age assessment: a deep learning case study on the Brazilian population with a supporting mobile application prototype*. Scientific Reports, 16(1), 4488. [https://doi.org/10.1038/s41598-025-34651-7](https://doi.org/10.1038/s41598-025-34651-7)

### BibTeX

```bibtex
@article{teodoro2026boneage,
  title={Automatic bone age assessment: a deep learning case study on the Brazilian population with a supporting mobile application prototype},
  author={Teodoro, Rafael do Amaral and de Lima, Filipe Verrone and Popa, Mirela and Sampaio, Gustavo Scalabrini and Kochi, Cristiane and Longui, Carlos Alberto and da Silva, Leandro Augusto},
  journal={Scientific Reports},
  volume={16},
  number={1},
  pages={4488},
  year={2026},
  publisher={Nature Publishing Group},
  doi={10.1038/s41598-025-34651-7}
}
```

Dataset and methodology are described in the associated publication:
[Scientific Reports paper](https://www.nature.com/articles/s41598-025-34651-7?utm_source=chatgpt.com)

---

### 📥 Download the Dataset

1. The dataset is provided as **`Data_UCI.zip`** in the TAG section.
2. You can either click on the TAG in the repository or directly use this link:
   [Download Data.zip](https://github.com/TeodoroRafael/BAA_data/releases/tag/Data)

---

### 📂 Dataset Contents

After extracting **`Data.zip`**, you will find:

* **`images/`** – A folder containing all radiographic images.
* **`Data_GP.csv`** – A CSV file with three columns:

  * **`ID`** – Unique identifier for each image (matches a file in the `images/` folder).
  * **`Sex`** – Binary value indicating gender (`F` = female, `M` = male).
  * **`Weight`** – Weight of the patient in kg (int).
  * **`Height`** – Height of the patient in cm (int).
  * **`Age`** – Chronological age of the patient (float).
  * **`Greulich Pyle`** – Greulich and Pyle bone age score.

---
