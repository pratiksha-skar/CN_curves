# Unveiling Arithmetic Statistics of Congruent Number Elliptic Curves via Data Science and Machine Learning

This repository contains the computational code accompanying the paper:

**"Unveiling Arithmetic Statistics of Congruent Number Elliptic Curves via Data Science and Machine Learning"**  
by *Priyavrat Deshpande, Aditya Karnataki, Pratiksha Shingavekar*, 2025.

The project explores arithmetic statistics of congruent number elliptic curves using tools from data science and machine learning.  
The repository contains SageMath notebooks for arithmetic computations and Python notebooks for statistical analysis and experiments.

---

## 📂 Repository Contents

- **SageMath Notebooks (`.ipynb`)**  
  Contain code for computing arithmetic invariants of congruent number elliptic curves, including:
  - $2$ and $3$-Selmer groups
  - MW ranks
  - Analytic ranks
  - BSD parameters like, regulator, special value. etc.
  - Frobenius traces

- **Python Notebooks (`.ipynb`)**  
  One notebook per experiment from the paper, covering:
  - Verification of **Heath-Brown heuristics** (files: HB2Theorem1 moments.ipynb, HB2Theorem2.ipynb)
  - Verification of **Poonen–Rains heuristics** (poonen_rains.ipynb)
  - Verification of **Delaunay heuristics** (delaunay..ipynb)
  - **Goldfeld’s conjecture** verification (goldfeld_conjecture_new.ipynb, goldfeld_conjcture_via_sampling.ipynb)
  - **Birch and Swinnerton-Dyer (BSD)** verification (bsd_verification_smith.ipynb)
  - **Averages of Frobenius traces** (frobenius_traces_CN_curves.ipynb)
  - **Distribution of MW ranks** (rank_moments.ipynb)
  - **Distribution of $3$-Selmer groups** (three_selmer_distribution.ipynb)
  - **Visualization of BSD parameters** (topology_bsd_parameters.ipynb)
  - **Machine learning models** for congruent number prediction (CN_bsd_classification.ipynb, CN_classification_arithmetic.ipynb, CN_prediction_frobenius_traces.ipynb, CN_prediction_selmerinfo.ipynb)

---

## 📊 Data

The datasets used in the experiments are hosted on Zenodo:  
👉 [https://doi.org/10.5281/zenodo.16731845]

The data is made available under the **Creative Commons Attribution 4.0 International License (CC BY 4.0)**.

---

## ⚡ Requirements

- [SageMath](https://www.sagemath.org/) (version 10.6, for number-theoretic computations)  
- Python ≥ 3.11  
- Jupyter Notebook  
- Common Python libraries: `numpy`, `pandas`, `matplotlib`, `scikit-learn`, `plotly`, 'seborn', 'pyarrow', 'kmapper', 'giotto-tda'


---
## How to use this repository?
- Clone this reporsitory.
- Launch Jupyter.
- Open any notebook and run cells sequentially (Sage notebooks should be run in a Sage-enabled Jupyter kernel. Python notebooks should be run in a standard Python kernel.)
---

## 📖 Reproducibility

Each notebook corresponds to a section/experiment from the paper.
Running them in order allows full reproduction of the computational results reported.
-Sage code explains how various parameters are calculated.
-Python notebooks implement statistical verification and ML models.

---

## 🤝 Contributing
This repository is primarily for reproducibility of results in the paper. Suggestions, corrections, and extensions are welcome via pull requests or issues.

---

## 📜 License

Code: Licensed under the MIT License.

Data: Licensed under the CC Attribution 4.0 International License (CC BY 4.0) (via Zenodo).

---

## 🙌 Acknowledgements

- SageMath and Python open-source communities
- Arithmetic statistics and number theory literature.
- Machine learning frameworks that made the ML experiments possible

  ---
  
