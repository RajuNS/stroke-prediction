# 🧠 Stroke Prediction Analysis

This project explores the [Stroke Prediction Dataset](https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset) to identify key risk factors and build a machine learning model to predict the likelihood of a stroke. The entire analysis and modeling process is documented in the Jupyter Notebook.



## Project Summary
- **Data Cleaning:** Handled missing values in the `bmi` column and preprocessed categorical features.
- **Exploratory Data Analysis (EDA):** Visualized relationships between health parameters (age, hypertension, etc.) and stroke risk.
- **Modeling:** Trained and evaluated several classification models, including Logistic Regression, Decision Tree, and Random Forest.
- **Results:** The final **Random Forest** model was the top performer, achieving an **F1-score of 97.5%** and an **AUC of 99.5%** after handling class imbalance with SMOTE.

## Key Findings
The most significant predictors for stroke were found to be:
1.  **Age**
2.  **Average Glucose Level**
3.  **Hypertension**

## How to Use This Repository

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/your-username/stroke-prediction-analysis.git](https://github.com/your-username/stroke-prediction-analysis.git)
    ```
2.  **Navigate into the project directory:**
    ```bash
    cd stroke-prediction-analysis
    ```
3.  **Install the required libraries:**
    ```bash
    pip install -r requirements.txt
    ```
4.  **Explore the analysis:** Open the `notebooks/stroke_prediction_notebook.ipynb` file in Jupyter Lab or Google Colab.