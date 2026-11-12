# Course Mini Projects — Python, Data Analysis and Machine Learning

A curated collection of **15 daily course assignments**, organized by topic and preserved with their original Jupyter notebooks, relevant datasets and available assignment briefs.

**Author:** Nikhil Khatri

> Scope note: This repository intentionally contains only the 15 daily assignments. The separate Hypothyroid Classification project (the 16th project in the source material) is excluded because it has its own repository.

## Project catalogue

| Day | Project | Category | Main focus |
|---:|---|---|---|
| 01 | Python Fundamentals and CSV-Based Data Handling | Python fundamentals | Python basics, CSV processing |
| 02 | Cereal Dataset Exploration with NumPy and Pandas | Python fundamentals | Data inspection, filtering, aggregation |
| 03 | Taxi Trip Distance, Outlier Detection and Fare Exploration | Data analysis | Distance calculations, outliers, visualization |
| 04 | Chemical Engineering Grades: Missing-Value Treatment and EDA | Data analysis | Missing data, descriptive statistics, EDA |
| 05 | Boston Housing: Simple Linear Regression | Regression | Simple linear regression and evaluation |
| 06 | House Price Prediction with Multiple, Ridge and Lasso Regression | Regression | Multiple regression and regularization |
| 07 | Diabetes Prediction with Logistic Regression | Classification | Logistic regression and evaluation |
| 08 | Diabetes Prediction with k-Nearest Neighbors | Classification | kNN and distance metrics |
| 09 | Diabetes Prediction with Support Vector Machines | Classification | SVM kernels and hyperparameters |
| 10 | Diabetes Prediction with Decision Trees | Classification | Decision-tree modeling |
| 11 | Diabetes Prediction with Ensemble Classifiers | Classification | Bagging, random forest, AdaBoost |
| 12 | Diabetes Prediction with Naive Bayes and Cross-Validation | Classification | Gaussian NB and cross-validation |
| 13 | Iris Dataset Clustering with K-Means | Unsupervised learning | Centroid-based clustering |
| 14 | Iris Dataset Clustering with DBSCAN | Unsupervised learning | Density-based clustering |
| 15 | Market Basket Analysis with Apriori | Association rules | Frequent itemsets and association rules |

## Repository structure

```text
course-mini-projects/
├── 01-python-fundamentals/
│   ├── day-01-.../
│   └── day-02-.../
├── 02-data-analysis-and-visualization/
│   ├── day-03-.../
│   └── day-04-.../
├── 03-regression-modeling/
│   ├── day-05-.../
│   └── day-06-.../
├── 04-supervised-classification/
│   ├── day-07-.../ through day-12-.../
├── 05-unsupervised-learning/
│   ├── day-13-.../
│   └── day-14-.../
├── 06-association-rule-mining/
│   └── day-15-.../
├── supporting-files/
├── requirements.txt
├── .gitignore
└── SOURCE_INVENTORY.md
```

Each assignment directory contains a detailed README, its original notebook, and the dataset(s) identified for that exercise. An assignment PDF is included when available in the source archives.

## Getting started

### 1. Clone the repository

```bash
git clone https://github.com/<your-username>/course-mini-projects.git
cd course-mini-projects
```

### 2. Create a virtual environment

```bash
python -m venv .venv
```

Activate it:

- Windows PowerShell: `.venv\Scripts\Activate.ps1`
- macOS/Linux: `source .venv/bin/activate`

### 3. Install dependencies

```bash
python -m pip install --upgrade pip
pip install -r requirements.txt
```

### 4. Launch Jupyter

```bash
jupyter notebook
```

Open the notebook inside the relevant assignment folder and run cells in order. Some original notebooks may assume a particular working directory or a dataset path; adjust the path locally if necessary.

## Main technologies

- **Language:** Python
- **Data analysis:** NumPy, Pandas
- **Visualization:** Matplotlib, Seaborn
- **Machine learning:** scikit-learn
- **Association-rule mining:** mlxtend
- **Notebook environment:** Jupyter

## Data and reproducibility notes

- The original notebooks have been preserved rather than silently refactored. Their code, assumptions and outputs may reflect the original course environment.
- Days 7–12: the source material contains repeated/identical CSV data files, and several notebooks refer to `Dataset_Day7.csv` even where an assignment brief names a day-specific file. The relevant supplied Day 7 dataset is included with these exercises; check each notebook's data path before running.
- Days 13–14: the supplied Iris CSV copies are identical; each assignment folder has its own copy for convenience.
- Some model searches, particularly SVM tuning, may take time. Reduce parameter grids or use a smaller sample when experimenting.
- No benchmark scores are asserted in this repository. Re-run notebooks to verify metrics in your own environment.
- Dependency versions are intentionally not pinned. For reproducible long-term execution, create and validate a lock file in the environment you use.

## Suggested improvements

- Refactor repeated notebook code into reusable Python modules.
- Add automated tests for data preparation and feature engineering.
- Record validated dependency versions and execution environments.
- Add plots and concise result summaries after rerunning each notebook.
- Add dataset source/licence information where it can be verified.

## Responsible use

These projects are educational exercises. Dataset provenance, redistribution permissions and privacy should be checked before making the repository public. Classification exercises using health-related data are for learning only and must not be used for medical diagnosis or treatment.

## License

No license is included because the original ownership and redistribution terms of all supplied course materials and datasets have not been independently established. Add a license only after confirming you have the right to redistribute the included content.
