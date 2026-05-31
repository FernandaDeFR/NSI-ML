# NSI-ML: Machine Learning for Non-Standard Interactions (JUNO)

This repository contains the analytical framework and Machine Learning models developed to simulate, classify, and analyze the effects of Non-Standard Interactions (NSI) on neutrino oscillation probabilities within the JUNO experimental framework.

## 📁 Repository Structure

* **`nsi_juno_v2.ipynb`**: Full data science and simulation pipeline:
  * Analytical simulation of $\nu_\mu \to \nu_e$ oscillation probabilities (Standard Model vs. NSI).
  * Synthetic dataset generation (50,000 events) incorporating experimental noise.
  * Performance comparison of three classifiers: **Random Forest**, **XGBoost**, and **MLP (Neural Network)**.
  * Sensitivity scans and feature importance analysis.
* **`relatorio.pdf`**: Comprehensive technical report detailing the underlying physics, matter potential equations, model performance metrics, and phenomenological discussions.

---

## 📌 Note on File Visualization

* **GitHub Preview Limit:** Due to the large size, high line count, and structural complexity of the notebook (`nsi_juno_v3.ipynb`), **GitHub may display an "An error occurred" message and fail to render the preview in the browser**.
* **Usage:** The file is completely intact. This error only affects GitHub's web interface. To use it:
  * **Download the file** directly to run it in your local environment (VS Code, Jupyter Lab, etc.).
  * Clone the repository via terminal:  
    ```bash
    git clone [https://github.com/FernandaDeFR/NSI-ML.git](https://github.com/FernandaDeFR/NSI-ML.git)
    ```

---

## 🛠️ Tech Stack

* **Environment:** Python 3.10
* **Data Processing:** `numpy`, `pandas`
* **Machine Learning:** `scikit-learn`, `xgboost`
* **Visualization:** `matplotlib`
