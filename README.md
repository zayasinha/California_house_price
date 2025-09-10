 🏠 California House Price

---

 📊 Project Overview

This project implements the foundational machine learning workflow from Aurélien Géron's *"Hands-On Machine Learning with Scikit-Learn, Keras & TensorFlow"*. The goal is to build a robust regression model to predict housing prices based on demographic and geographic data such as population, median income, and location.

The notebook serves as a practical demonstration of building a production-ready ML pipeline, emphasizing the critical steps of feature engineering, model selection, and hyperparameter tuning.

---

 🛠️ Tech Stack & Skills Demonstrated

*   **Programming Language:** Python
*   **Libraries & Frameworks:**
    *   `pandas`, `NumPy` (Data Manipulation & Analysis)
    *   `Matplotlib`, `Seaborn` (Data Visualization & EDA)
    *   `Scikit-Learn` (Machine Learning Pipeline: Preprocessing, Models, Evaluation)
*   **Machine Learning:**
    *   **Data Preprocessing:** Handling missing values, feature scaling (`StandardScaler`).
    *   **Feature Engineering:** Creating new relevant features (e.g., `rooms_per_household`, `bedrooms_per_room`).
    *   **Model Training:** Linear Regression, Decision Trees, Ensemble Methods (Random Forest).
    *   **Model Evaluation:** Cross-Validation, Hyperparameter Tuning (`GridSearchCV`), Analysis of error metrics (RMSE, MAE).
*   **Software:** Jupyter Notebook

---

 📈 Key Steps in the Workflow

1.  **Data Acquisition & Inspection:** Loaded the dataset and performed initial exploration to understand its structure, statistics, and identify potential issues.
2.  **Data Visualization & EDA:** Created insightful visualizations (histograms, scatter plots, geographic data plots) to uncover patterns, correlations, and anomalies.
3.  **Data Preprocessing:** Designed a pipeline to handle numerical data, impute missing values, and scale features for model consumption.
4.  **Feature Engineering:** Engineered new features that have a stronger correlation with the target variable (`median_house_value`).
5.  **Model Selection & Training:** Trained and compared multiple regression algorithms to establish a baseline and identify the most promising model.
6.  **Fine-Tuning:** Utilized `GridSearchCV` to perform an exhaustive search for the best hyperparameters for the chosen model (Random Forest Regressor), optimizing performance.
7.  **Evaluation & Analysis:** Evaluated the final model on a held-out test set, analyzed the types of errors it made, and discussed its limitations and potential improvements.

---

 🚀 Results & Performance

The final tuned model achieved a significant performance improvement over the initial baseline.

*   **Final Test Set RMSE:** `~$48,000`
*   This means the model's predictions are, on average, within **$48,000** of the actual home prices.

This error is evaluated in the context of the data, where home values range from `$50,000` to `$500,000`, demonstrating a solid predictive capability.

---

## 📁 Repository Structure
