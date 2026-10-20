# Medical Insurance Premium Prediction

## Project Overview

The **Medical Insurance Premium Prediction** project uses machine learning to predict medical insurance premium costs based on customer and health-related attributes. It involves data cleaning, exploratory data analysis (EDA), data visualization, model training, and performance evaluation.

## Objectives

- Understand and preprocess medical insurance data.
- Perform exploratory data analysis to identify patterns and relationships.
- Visualize the factors associated with insurance premium costs.
- Train and compare multiple machine learning regression models.
- Evaluate model performance using standard regression metrics.

## Technologies Used

- **Programming Language:** Python
- **Data Analysis:** Pandas, NumPy
- **Data Visualization:** Matplotlib, Seaborn
- **Machine Learning:** Scikit-learn
- **Environment:** Jupyter Notebook

## Machine Learning Models

The following regression models were trained and evaluated:

1. Linear Regression
2. Decision Tree Regressor
3. Random Forest Regressor

## Model Evaluation

The models were evaluated using R² Score, Mean Absolute Error (MAE), Mean Squared Error (MSE), and Root Mean Squared Error (RMSE).

| Model | R² Score | MAE | MSE | RMSE |
|---|---:|---:|---:|---:|
| Linear Regression | 0.7140 | 2583.00 | 12,196,880 | 3492.40 |
| Decision Tree | 0.5967 | 1270.20 | 17,198,230 | 4147.08 |
| Random Forest | **0.8899** | **1074.37** | **4,693,948** | **2166.55** |

**Best-performing model:** Random Forest Regressor, with an R² score of approximately **0.89**.

The Random Forest model achieved the highest R² score and the lowest MAE and RMSE among the three evaluated models.

## Project Workflow

1. Loaded and explored the medical insurance dataset.
2. Cleaned and prepared the data for analysis.
3. Performed exploratory data analysis and visualizations.
4. Prepared the features and target variable for regression.
5. Trained Linear Regression, Decision Tree, and Random Forest models.
6. Evaluated and compared the models using regression metrics.
7. Identified Random Forest as the best-performing model among those tested.

## How to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/mohammadyousuf-63/Medical_Insurance_Premium_Prediction.git
```

### 2. Navigate to the Project Directory

```bash
cd Medical_Insurance_Premium_Prediction
```

### 3. Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open the project's notebook and run the cells in order.

## Project Structure

```text
Medical_Insurance_Premium_Prediction/
├── insurance_prediction.ipynb
├── README.md
└── dataset file(s)
```

*Note: The exact files and folders depend on the contents of the repository.*

## Key Learnings

- Data cleaning and preprocessing using Pandas and NumPy.
- Exploratory data analysis and data visualization.
- Training and evaluating regression models.
- Comparing model performance using multiple evaluation metrics.
- Selecting a suitable model based on experimental results.

## Future Improvements

- Perform hyperparameter tuning to improve model performance.
- Explore additional regression algorithms.
- Improve model generalization through cross-validation.
- Develop a simple interface for interactive premium predictions.

## Author

**Mohammad Yousuf**

- GitHub: [mohammadyousuf-63](https://github.com/mohammadyousuf-63)

---

*This project was developed for learning and demonstrating practical machine learning and data analysis skills.*
