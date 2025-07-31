# Startup_Prediction_Model_
# 🚀 Startup Investment Analysis with Random Forest Classifier

This project analyzes startup investment data and applies machine learning techniques to predict outcomes related to startup funding. It uses a Random Forest Classifier to build a predictive model based on historical venture capital data.

## 📂 Project Overview

The notebook walks through the full machine learning pipeline:

* Loading and cleaning venture capital investment data
* Feature engineering and selection
* Data preprocessing and scaling
* Building and tuning a Random Forest Classifier
* Evaluating performance using metrics like confusion matrix and ROC AUC
* Visualizing feature importance and results

## 📊 Dataset

* Source: `investments_VC.csv`
* Encoding: `ISO-8859-1`
* Features used: Funding rounds, funding type (seed, venture, etc.), market category, region, founding year, and more.
* Target variable: Startup funding success or stage (`status` column).

## ⚙️ Model Details

* Algorithm: Random Forest Classifier
* Libraries Used: `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`
* Evaluation Metrics:

  * Confusion Matrix
  * Classification Report
  * ROC AUC Score

## 📈 Visualizations

* Data distributions
* Correlation heatmaps
* Feature importance from the trained model

## 📁 How to Use

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/startup-investment-model.git
   cd startup-investment-model
   ```

2. Open the notebook:

   ```bash
   jupyter notebook model.ipynb
   ```

3. Follow through the cells to explore data analysis, model training, and results.

## ✅ Key Outcomes

* Identified key factors influencing startup funding outcomes.
* Achieved predictive performance using a Random Forest model.
* Provided visual insights into investment patterns and startup attributes.

## 🛠 Tools Used

* Python
* Jupyter Notebook
* Pandas, NumPy
* Scikit-learn
* Matplotlib, Seaborn

