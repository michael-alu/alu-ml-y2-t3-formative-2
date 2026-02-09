# PCA for Malaria Dataset in Africa

This repository contains my solution for the **Formative Assignment: Advanced Linear Algebra (PCA)**.
The goal is to implement **Principal Component Analysis (PCA)** from scratch using NumPy, apply it to an
African dataset, and document how to use the code as a small Python library.

---

## 1. Project overview

**Topic**:

PCA from scratch (no `sklearn.PCA`) on an African public–health dataset.

**Dataset**:

Malaria in Africa by **Lydia70** on Kaggle

**Link**:

`https://www.kaggle.com/datasets/lydia70/malaria-in-africa`

**Main Notebook**:

`Michael_Nwuju_PCA_Formative_1.ipynb`

In the notebook, I:

- Load and clean the malaria dataset.
- Handle missing values by putting the mean of the dataset.
- Use one‑hot encoding to numerically encode non-numeric fields.
- Standardize all features using NumPy only.
- Compute the covariance matrix, eigenvalues and eigenvectors.
- Sort eigenvalues/eigenvectors in descending order.
- Dynamically choose the number of principal components based on explained variance.
- Project the data onto the selected principal components.
- Visualize the data before and after PCA.

---

## 2. Requirements

You can use any recent Python 3 version (e.g. 3.10+). The only dependencies are:

- `numpy`
- `pandas`
- `matplotlib`

Install them with:

```bash
pip install numpy pandas matplotlib
```

Alternatively, you can simply upload the notebook to **Google Colab**, where you typically do not need to install these dependencies.

---

## 3. Running the notebook

1. Clone the GitHub repository where this notebook lives:

   ```bash
   git clone https://github.com/michael-alu/alu-ml-y2-t3-formative-2.git
   cd alu-ml-y2-t3-formative-2
   ```

2. Launch Jupyter from the folder that contains `Michael_Nwuju_PCA_Formative_1.ipynb`:

   ```bash
   jupyter notebook
   ```

3. Open `Michael_Nwuju_PCA_Formative_1.ipynb` and run the cells from top to bottom.
