# Predicting Social Media E-Commerce Conversions

**Course:** ISOM 835 – Predictive Analytics and Machine Learning  
**Institution:** Sawyer Business School, Suffolk University  

## Project Summary
In the modern digital economy, understanding how different demographics interact with social media platforms is a fundamental business necessity. This project applies the complete machine learning lifecycle to analyze user behavior within social media environments. The analysis focuses on forecasting e-commerce conversions, addressing class imbalance in predictive modeling, and evaluating the impact of digital habits on user well-being.

## Project Objectives
This analysis aims to accomplish the following core objectives:
* **Exploratory Data Analysis (EDA):** Identify patterns, distributions, and behavioral anomalies within social media usage data across different demographics.
* **Data Preprocessing:** Prepare a multidimensional dataset for machine learning through categorical encoding, feature scaling, and train/test splitting.
* **Predictive Modeling:** Train, tune, and evaluate at least two classification models (Logistic Regression and a hyperparameter-tuned Random Forest) to predict whether a user will make a purchase via social media.
* **Business Insight Generation:** Extract actionable recommendations for digital marketing strategies, targeted advertising, and platform design based on feature importance and model evaluation metrics.

## Dataset Description and Source
* **Name:** Social Media User Behavior
* **Source:** Open Data Portals / Kaggle
* **Description:** A robust, non-trivial dataset containing 2,000 unique user observations across 34 diverse features. It blends continuous numerical data (e.g., age, followers, daily usage hours) with categorical variables (e.g., primary platform, profession, sleep disruption) to provide a holistic view of the digital consumer. The target variable for classification is `purchased_via_social_media`.

##Visuals and Synopsis

## Tools and Libraries Used
* **Language:** Python
* **Environment:** Google Colab
* **Data Manipulation:** `pandas`, `numpy`
* **Data Visualization:** `matplotlib`, `seaborn`
* **Machine Learning:** `scikit-learn` (LogisticRegression, RandomForestClassifier, StandardScaler, GridSearchCV, ConfusionMatrixDisplay)

## Instructions: How to Open, Run, and View Results

The analysis, modeling, and visualizations were conducted entirely within a Google Colab notebook. 

https://colab.research.google.com/drive/1P7u0sUMh_xmhFr-UESEMhx8JUTdtVQNd?usp=sharing

**To reproduce the analysis and view the results:**
1. Click the link above to open the notebook in Google Colab.
2. Download the `social_media_user_behavior.csv` dataset directly from this GitHub repository.
3. In the Google Colab environment, click the **Folder icon** on the far-left sidebar to open the Files panel.
4. Click the **Upload icon** (or drag and drop) to upload the `social_media_user_behavior.csv` file into the Colab session space.
5. In the top menu bar, click **Runtime** > **Run all**. 
6. Scroll through the notebook to view the executed code, the generated EDA visualizations, the hyperparameter tuning progress, and the final model evaluation metrics (Accuracy, F1-Score, and Confusion Matrix).
* `country_vs_usage.png`
* `profession_vs_usage.png`
