# Machine Learning Notebooks - WEEK3_ML_BASELIN_SYSTEM

Hello! This repository contains several **Jupyter Notebooks** I created as part of the Machine Learning projects in Week 3 of SDAIA.

The goal of these projects is to **apply basic machine learning concepts on different datasets** and experiment with classification models while analyzing their results.

---

## 🗂️ Files Included

1. **Penguins Dataset Notebook (`penguinss.ipynb`)**  
   - Analyzes the **Penguins dataset**.  
   - Trains a **Linear Regression** model to predict the birds' weight (`body_mass_g`) using features like bill length and flipper length.  
   - Uses **scaling** and **Gradient Descent** for model approximation.  
   - Visualizes the data and the final model.  

2. **Titanic Classification Notebook (`Titanic ML.ipynb`)**  
   - Analyzes the **Titanic dataset** and predicts passenger survival (`Survived`).  
   - Data cleaning (filling missing values, encoding categorical variables).  
   - Compares performance of several classification models:
     - Logistic Regression
     - Random Forest
     - Support Vector Machine (SVM)
     - Baseline (Most Frequent)  
   - Calculates metrics: Accuracy, Precision, Recall, F1 Score  
   - Visualizes **Confusion Matrices** for each model for easier understanding.  

3. **Fruit Datasets Notebook (`Fruit Datasets.ipynb`)**  
   - Loads and analyzes **Date Fruit** data from Hugging Face Dataset.  
   - Prepares the data for future machine learning applications.  
   - This notebook focuses on **loading and handling the dataset programmatically**.  

---

## ⚡ General Notes

- All notebooks use **Python** and **Jupyter Notebook**.  
- Main libraries used: `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`.  
- Main goal: **Understand the steps of building machine learning models from scratch to evaluation**.  
- Notebooks are structured so anyone can follow the steps:  
  1. Explore the data  
  2. Clean and transform the data  
  3. Build and train the model  
  4. Evaluate results and visualize metrics  

---

## 📌 How to Use

1. Clone this repository:
   ```bash
   git clone https://github.com/janahussein2/WEEK3_ML_BASELIN_SYSTEM.git
