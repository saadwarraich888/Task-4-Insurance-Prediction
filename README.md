# Task 4: Predicting Insurance Claim Amounts

## Objective
Estimate medical insurance claim amounts based on personal data such as age, BMI, gender, and smoking status using a **Linear Regression** model.

---

## Dataset
**Medical Cost Personal Dataset (`insurance.csv`)**  

The dataset contains the following columns:

| Column       | Description                                      |
|-------------|--------------------------------------------------|
| age         | Age of the individual                            |
| sex         | Gender (male/female)                             |
| bmi         | Body Mass Index                                  |
| children    | Number of children                               |
| smoker      | Smoking status (yes/no)                          |
| region      | Residential area (northeast, southeast, etc.)   |
| charges     | Medical insurance charges (target variable)     |

---

## Key Features of This Project
- **Data Cleaning and Preprocessing**: Handle missing values and encode categorical variables.  
- **Exploratory Data Analysis (EDA)**: Visualize relationships between features and insurance charges.  
- **Linear Regression Model**: Train a model to predict insurance charges.  
- **Evaluation Metrics**: Assess model performance using **MAE (Mean Absolute Error)** and **RMSE (Root Mean Squared Error)**.  

---

## Insights
- **Smoking status** has the strongest impact on insurance charges.  
- **Age** and **BMI** positively correlate with charges.  
- Linear Regression provides an **interpretable and effective model** for predicting medical costs.  

---

## Visualizations
- Distribution of charges by **smoking status**  
- Relationship between **BMI and charges**  
- Relationship between **age and charges**  
- Pair plots and correlation analysis for numerical features  

---

## Tools & Libraries
- **Python**  
- **Pandas**  
- **NumPy**  
- **Matplotlib**  
- **Seaborn**  
- **Scikit-learn**  

---

## How to Run
1. Clone the repository:

```bash
git clone https://github.com/saadwarraich888/Task-4-Insurance-Prediction.git