## Objective

The primary objective of this project is to implement and evaluate different regression techniques for predicting medical insurance charges. The project focuses on **model evaluation and refinement** using:

- Single Variable Linear Regression
- Multiple Linear Regression
- Ridge Regression (L2 Regularization)

other concepts: 

- Feature Scaling using `StandardScaler`
- Polynomial Feature Engineering
- Training Pipeline
- Model Evaluation using the **R² Score**

### Workflow

- Load the insurance dataset into a Pandas DataFrame.
- Clean the dataset by handling missing and invalid values.
- Perform Exploratory Data Analysis (EDA) to identify the features that most influence insurance charges.
- Build and evaluate a Single Variable Linear Regression model.
- Build and evaluate a Multiple Linear Regression model using all relevant features.
- Create a machine learning pipeline for preprocessing and model training.
- Apply Polynomial Feature transformation to capture non-linear relationships.
- Improve model performance using Ridge Regression and compare the results.

---

## Dataset Information

The dataset contains demographic and health-related information used to predict annual medical insurance charges.

| Feature | Description | Data Type |
|---------|-------------|-----------|
| `age` | Age of the individual (years) | Integer |
| `gender` | Gender (1 = Female, 2 = Male) | Integer |
| `bmi` | Body Mass Index | Float |
| `no_of_children` | Number of dependent children | Integer |
| `smoker` | Smoking status (0 = Non-smoker, 1 = Smoker) | Integer |
| `region` | US region (1 = Northwest, 2 = Northeast, 3 = Southwest, 4 = Southeast) | Integer |
| `charges` | Annual medical insurance charges (USD) | Float |

---

*practice project*
