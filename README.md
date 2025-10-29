# 🚀 Extreme Learning Machine (ELM) for Regression & Multiclass Classification

### 🧠 Overview

This project implements and evaluates the **Extreme Learning Machine (ELM)** algorithm for **regression** and **multiclass classification** tasks.
ELM is a **fast and efficient learning method** for *single-hidden-layer feedforward neural networks (SLFNs)* — offering **non-iterative training** and **strong generalization** compared to traditional methods like SVM, Random Forest, and MLP.

The project includes:

* Mathematical modeling of ELM
* Experimental comparisons with standard ML algorithms
* Visualization and evaluation across popular datasets

---

## 📋 Project Scope

This repository covers:

* **Extreme Learning Machine (ELM)** for both **regression** and **multiclass classification**
* **Algorithm comparison** with:

  * Support Vector Machine (SVM)
  * Random Forest (RF)
  * Multi-Layer Perceptron (MLP)
* **Datasets used:** MNIST, Boston Housing, Iris

---

## ✨ Features

✅ ELM implementation for:

* **Regression:** Predict continuous values (e.g., housing or stock prices)
* **Multiclass Classification:** Handwritten digit or image recognition

✅ **Comparative Analysis:** SVM, Random Forest, and MLP

✅ **Datasets Supported:**

* [MNIST](http://yann.lecun.com/exdb/mnist/)
* [Boston Housing](https://scikit-learn.org/stable/datasets/toy_dataset.html#boston-house-prices-dataset)
* [Iris](https://scikit-learn.org/stable/datasets/toy_dataset.html#iris-plants-dataset)

✅ **Visualizations:**

* Accuracy and loss charts
* Activation pattern plots
* Confusion matrices

✅ **Evaluation Metrics:**

* Accuracy
* RMSE (Root Mean Square Error)
* Precision
* Recall
* F1-Score

---

## 🛠️ Technologies Used

* **Programming Language:** Python
* **Libraries:**

  ```bash
  NumPy
  Scikit-learn
  Matplotlib
  ```

---

## ⚙️ Installation

Clone this repository:

```bash
git clone <your-repo-url>
cd <your-repo-directory>
```

Install required packages:

```bash
pip install numpy scikit-learn matplotlib
```

---

## ▶️ Usage

Run the main script to train and evaluate the ELM model:

```bash
python elm.py
```

You can adjust scripts or configurations for:

* Different datasets
* Regression or classification tasks

All generated **visualizations** and **reports** will be saved in the `/visualizations` or `/output` directory.

---

## 📂 Project Structure

```bash
Extreme-Learning-Project/
│
├── elm.py                  # Core ELM implementation
├── experiments/            # Regression & classification experiments
├── data/                   # Sample datasets (MNIST, Iris, Boston Housing)
├── visualizations/         # Plots & charts output
├── README.md               # Project documentation
└── requirements.txt        # Dependencies
```

---

## 📈 Results

Comparative results will include:

* Training time
* Accuracy/RMSE
* Confusion matrix
* Visualization of ELM activation and output layers

---

## 📚 References

* Huang, G.-B., Zhu, Q.-Y., & Siew, C.-K. (2006). *Extreme Learning Machine: Theory and Applications*. **Neurocomputing**.
* Huang, G.-B., Wang, D., & Lan, Y. (2011). *Extreme Learning Machines: A Survey*. **International Journal of Machine Learning and Cybernetics**.
* Huang, G.-B., & Chen, L. (2008). *Enhanced Random Search Based Incremental Extreme Learning Machine*. **Neurocomputing**.

---

## 💡 Future Work

* Integrate deep ELM variants
* Add hyperparameter optimization (random/Bayesian search)
* Extend to multi-output regression tasks

---
