# Household Water Consumption Prediction Using Machine Learning

## 📌 Project Overview

This project focuses on predicting household water consumption using machine learning techniques. The objective is to analyze household and environmental data, identify patterns in water usage, and build predictive models that may support better water-consumption planning.

## 🎯 Objectives

- Explore factors associated with household water consumption.
- Clean and prepare the dataset for analysis.
- Perform Exploratory Data Analysis (EDA) to understand patterns and relationships.
- Build and compare multiple regression models.
- Evaluate model performance using appropriate regression metrics.

## 📂 Dataset

The dataset used in this project was obtained from:

**Source:** [Household Water Consumption Pattern Dataset](https://github.com/Harshita1375/Household_water_consumption_pattern)

The dataset contains household water-consumption information and related features used for model development.

*Note: The dataset is sourced externally and should be obtained from the original source before running the notebook, if it is not included in this repository.*

## 🛠️ Technologies Used

- **Python** – data analysis and model development
- **Pandas** – data manipulation and cleaning
- **NumPy** – numerical operations
- **Matplotlib** – data visualization
- **Seaborn** – statistical visualization
- **Scikit-learn** – machine learning and model evaluation
- **Jupyter Notebook** – interactive development

## 🔍 Project Workflow

1. **Data Loading:** Loaded the dataset and examined its structure.
2. **Data Preprocessing:** Inspected missing values and prepared the data for modeling.
3. **Exploratory Data Analysis:** Explored the dataset to understand distributions, patterns, and relationships.
4. **Model Development:** Built three regression models:
   - Linear Regression
   - Decision Tree Regression
   - Random Forest Regression
5. **Model Evaluation:** Compared predictions with actual values using MAE, RMSE, and R² score.
6. **Model Comparison:** Identified Random Forest Regression as the best-performing model among the evaluated models.

## 📊 Model Performance

The following results were obtained during model evaluation:

| Model | MAE | RMSE | R² Score |
|---|---:|---:|---:|
| Linear Regression | 26.14 | 35.16 | 0.779 |
| Decision Tree Regression | 18.89 | 27.38 | 0.866 |
| Random Forest Regression | 11.79 | 18.26 | 0.940 |

**Best-performing model:** Random Forest Regression

The Random Forest model achieved an R² score of 0.940 on the test data. It also recorded the lowest MAE and RMSE among the three models, indicating better predictive performance on the evaluated test set.

*MAE and RMSE are expressed in the target variable's units. R² measures how well the model explains variation in the target values.*

## ▶️ How to Run the Project

1. Clone or download this repository.
2. Install Python and Jupyter Notebook.
3. Install the required libraries:

   `pip install pandas numpy matplotlib seaborn scikit-learn jupyter`

4. Download the dataset from the source linked above.
5. Place the dataset in the location expected by the notebook, or update the file path in the code.
6. Open the notebook `smlminiproject (1).ipynb`.
7. Run the cells in sequence to perform the analysis and evaluate the models.

## 💡 Key Learnings

- Data preprocessing and handling missing values
- Exploratory Data Analysis and data visualization
- Training and comparing regression models
- Evaluating model performance using regression metrics
- Using Python libraries to solve a practical prediction problem

## ⚠️ Limitations

The model's predictions depend on the quality and coverage of the dataset. The reported evaluation scores reflect performance on the test data used in this project and do not guarantee the same accuracy for every household or real-world situation.

## 🚀 Future Improvements

- Improve feature selection and preprocessing.
- Tune model hyperparameters to explore potential performance improvements.
- Test the model on additional or more recent household water-consumption data.
- Develop a simple interface to demonstrate predictions, if suitable data and validation are available.

## 👩‍💻 Author

**Esha Rasam**

B.Sc. Data Science Student | Aspiring Data Analyst

## 📎 Repository

[View the project on GitHub](https://github.com/Esha7058/Household-Water-Consumption-Prediction)
