# Intro to Python – Assessment Submission

This repository contains my Python assessment submission for the KCL module, demonstrating core Python concepts including variables, basic arithmetic, data structures, and simple data dictionaries.

## 📁 Contents

- `python_submission.html`  
  Exported HTML version of the notebook showing all code cells, outputs, and answers to the assignment tasks.
- `python_submission.ipynb`
  Original notebook with the code 

## 🧠 Topics Covered

- Creating and working with basic Python objects (strings, integers, floats)
- Arithmetic operations and use of the `math` library (e.g., square roots, casting to integers)
- Lists: creation, length, nesting lists, and type checking
- Dictionaries: creating keyed data structures for participants and scores
- Accessing, updating, and extending dictionary entries (including handling `None` / null values)

## 🤖 Machine learning & Alzheimer’s modelling

Later sections of the assignment extend these foundations to an applied machine learning task using a neuroimaging dataset (MCI and healthy participants) with cognitive scores relevant to Alzheimer’s disease progression.[file:58] The workflow includes data cleaning and preprocessing (handling missing values, standardisation) and the use of dimensionality reduction / feature selection to control overfitting when working with many imaging features.

Classification models (e.g., logistic regression and tree‑based methods) are trained to predict whether individuals with Mild Cognitive Impairment (MCI) will convert to Alzheimer’s disease, evaluated with metrics such as accuracy, precision, and recall. In parallel, regression models are built to predict Alzheimer’s Disease Assessment Scale (ADAS) scores from imaging and cognitive features, with performance assessed using measures like RMSE and \(R^2\).

Kernel‑based correlation analysis and feature clustering are used to explore relationships between brain volumes (such as hippocampal and ventricular measures) and cognitive performance, informing which predictors are most informative for the models.[file:58] Feature selection and dimensionality reduction techniques (e.g., PCA or similar approaches) are applied to retain the most relevant imaging and demographic variables while reducing redundancy.

Overall, the assignment shows how basic Python, data structures, and libraries can be combined into an end‑to‑end pipeline: from exploratory analysis and feature engineering through to model training, evaluation, and interpretation in a clinical research context.

## 🧪 Example Tasks (Concepts)

Some of the key exercises included:

- Building simple print statements that combine text and computed values using f-strings
- Constructing a list (`my_list`) containing mixed data types such as numbers, types, and nested lists
- Creating a `sample_scores` dictionary mapping participant IDs to pairs of verbal and delayed memory scores
- Updating individual entries (e.g., changing a participant’s delayed memory score)
- Adding a new participant with partial data (verbal memory as `None`, delayed memory provided)

## 📦 How to View

You can view the submission directly in your browser by opening the HTML file on GitHub and using the “Raw” or “Download” option.
If you prefer a notebook format, you can import the code into a Jupyter notebook or VS Code and rerun the cells there.

## 🔍 Purpose

The goal of this project is to demonstrate foundational Python skills for psychological and data analysis contexts, focusing on clear, well-commented code and correct use of core data structures.[file:58]
