# Lung Cancer Analysis

![Lung Cancer Analysis](https://img.shields.io/badge/Lung%20Cancer-Analysis-blue)  
This repository contains a comprehensive analysis of lung cancer data. It integrates exploratory data analysis (EDA), survival analysis, predictive modeling, and explainability techniques to derive meaningful insights into lung cancer outcomes and prognosis.

---

## Table of Contents
- [Lung Cancer Analysis](#lung-cancer-analysis)
  - [Table of Contents](#table-of-contents)
  - [Overview](#overview)
  - [Features](#features)
  - [Technologies Used](#technologies-used)
  - [How to Run](#how-to-run)
  - [Notebook Highlights](#notebook-highlights)
  - [Contributions](#contributions)
    - [How to Contribute](#how-to-contribute)
  - [License](#license)

---

## Overview
Lung cancer is one of the leading causes of cancer-related deaths worldwide. This project aims to analyze key factors influencing survival and metastasis outcomes using a combination of machine learning and survival regression techniques.

**Key Objectives:**
- Identify significant features impacting lung cancer outcomes.
- Predict metastasis using advanced machine learning models.
- Perform survival analysis to estimate life expectancy based on patient characteristics.

---

## Features
1. **Data Preprocessing**
   - Handling missing values and outliers.
   - Encoding categorical variables for machine learning models.

2. **Exploratory Data Analysis (EDA)**
   - Visualizations of age, smoking history, and cancer stage.
   - Heatmaps, pairplots, and custom visualizations for advanced insights.

3. **Predictive Modeling**
   - Gradient Boosting and Random Forest models for metastasis prediction.
   - Hyperparameter tuning using GridSearchCV.

4. **Survival Analysis**
   - Kaplan-Meier curves for survival probabilities.
   - Cox Proportional Hazards model for advanced survival regression.

5. **Model Explainability**
   - SHAP analysis for feature importance visualization.

6. **Clustering**
   - K-Means clustering to group patients with similar characteristics.

---

## Technologies Used
- **Python** for data analysis and modeling.
- **Pandas**, **NumPy** for data manipulation.
- **Matplotlib**, **Seaborn** for visualizations.
- **Scikit-learn** for machine learning models.
- **Lifelines** for survival analysis.

---

## How to Run
1. **Clone the Repository**
   ```bash
   git clone https://github.com/disha-karmakar/Lung-Cancer-Analysis.git
   cd Lung-Cancer-Analysis

2. **Install Dependencies**

- Ensure you have Python 3.7+ installed.
- Install the required libraries:
    ```bash
    pip install -r requirements.txt

3. **Run the Notebook**

- Open the Jupyter Notebook:
    ```bash
    jupyter notebook Lung_Cancer_Analysis.ipynb

---

## Notebook Highlights
- **Data Insights:** Detailed visualizations highlighting demographic and behavioral patterns.
- **Predictive Modeling:** Implementation of Random Forest and Gradient Boosting for metastasis prediction.
- **Survival Analysis:** Kaplan-Meier and Cox models to estimate survival probabilities.
- **Clustering:** K-Means clusters reveal distinct patient groups.
---
## Contributions
Feel free to contribute to this project by opening issues or submitting pull requests.

### How to Contribute
1. Fork the repository.
2. Create a feature branch.
3. Commit your changes.
4. Open a pull request.
---
## License
This project is licensed under the MIT License.See the [LICENSE](LICENSE) file for details.

---