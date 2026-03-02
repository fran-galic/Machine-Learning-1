# Machine Learning 1 (Strojno učenje 1)

**Academic year:** 2025/2026  
**Faculty of Electrical Engineering and Computing (FER), University of Zagreb**  
**Course page:** http://www.fer.unizg.hr/predmet/struce1

---

## Course Instructors
- Prof. Jan Šnajder, PhD
- Assoc. Prof. Marko Đurasević, PhD
- Prof. Stjepan Picek, PhD
- Dr. Josip Jukić

## Teaching Assistants (Laboratory)
- Ana Barić, MSc in Computer Engineering
- Dr. Josip Jukić
- Karlo Koledić, MSc in Electrical Engineering and Information Technology
- Marko Čuljak, MSc in Computer Engineering

---

## Course Description
Machine learning is a branch of artificial intelligence focused on designing algorithms that improve their performance based on empirical data. The course covers the theory and principles of machine learning, along with an overview of its applications in data analysis, computer vision, bioinformatics, and computational linguistics. The focus is on supervised learning (classification and regression) and unsupervised learning (clustering and dimensionality reduction).

---

## Prerequisites
- Introduction to Programming
- Algorithms and Data Structures
- Mathematical Analysis 1 and 2
- Discrete Mathematics
- Linear Algebra
- Probability and Statistics
- Information Theory
- Solid knowledge of Python programming

---

## Learning Outcomes
Upon successful completion of the course, students will be able to:
- Define the fundamental concepts of machine learning
- Differentiate between generative and discriminative, parametric and non-parametric, as well as probabilistic and non-probabilistic models
- Explain the theoretical assumptions, strengths, and limitations of core machine learning algorithms
- Apply model selection procedures and statistical evaluation of learned models
- Implement and evaluate various classification algorithms (generative, discriminative, non-parametric)
- Apply clustering algorithms and methods for cluster validation
- Design and implement a procedure for classification/clustering of data and conduct its evaluation
- Assess the suitability of machine learning algorithms for a given task

---

## Repository Structure
This repository contains my coursework for **Machine Learning 1**, organized by **laboratory exercises** and **homework assignments**.

```text
Machine-Learning-1/
├─ homework/
│  ├─ homework_1/
│  ├─ homework_2/
│  ├─ homework_3/
│  ├─ homework_4/
│  └─ homework_5/
├─ lab0/
│  ├─ numpy_tryout.ipynb
│  ├─ matplotlib_tryout.ipynb
│  └─ SU1-2025-LAB0.ipynb
├─ lab1/
│  └─ SU1-2025-LAB1-Galic-Fran.ipynb
├─ lab2/
│  └─ SU1-2025-LAB2-Galic-Fran.ipynb
├─ lab3/
│  └─ SU1-2025-LAB3-Galic-Fran.ipynb
├─ lab4/
│  └─ SU1-2025-LAB4-Galic-Fran.ipynb
├─ .gitignore
├─ .pre-commit-config.yaml
├─ .python-version
├─ LICENSE
├─ pyproject.toml
├─ uv.lock
└─ README.md
```

---

## Laboratory Exercises (Short Overview)

- **Lab 0 - Python/Numpy/Matplotlib warm-up**
  - Quick refreshers and plotting / array manipulation basics.

- **Lab 1 - Linear Regression**
  - Simple linear regression, polynomial regression, model selection
  - Regularization (L1 vs L2 / Ridge), feature scaling, multicollinearity

- **Lab 2 - Linear Discriminative Models & Logistic Regression**
  - Linear regression as a classifier, multiclass classification
  - Logistic regression: analysis, regularization, feature mapping

- **Lab 3 - SVM & Non-parametric Methods**
  - Linear and non-linear SVM (kernels), hyperparameter tuning
  - Standardization effects, k-NN, curse of dimensionality / irrelevant features

- **Lab 4 - Parameter Estimation, Probabilistic Graphical Models, Clustering**
  - MLE vs MAP, Bayes networks and explaining away
  - k-means, Gaussian Mixture Models (GMM), clustering evaluation

---

## Homework
Homework assignments are stored under `homework/homework_{k}/` (1–5). Each folder contains the corresponding task materials and my solutions (as provided/required in the course).

---

## Environment / Running Notebooks
This repo uses a Python environment tracked via `pyproject.toml` and `uv.lock`.

```bash
# create/sync the environment
uv sync


# run Jupyter (example)
uv run jupyter lab
```

> Note: exact commands may depend on your local setup (Jupyter installed in the env, etc.).

---

## Notes
- This repository is intended for personal coursework organization and reproducibility.
- If you are taking the course, please follow FER rules on academic integrity.

---