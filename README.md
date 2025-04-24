#  Task 1: Data Cleaning process for Machine Learning



## Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Dataset
We are using the **Titanic Dataset** from Kaggle.

[Click here to download the dataset](https://www.kaggle.com/competitions/titanic/data)

---

##  Steps Covered

1. **Import Dataset & Explore Basic Info**
   - Understand data types, null values, and statistical summary.

2. **Handle Missing Values**
   - Filled missing `Age` with median.
   - Filled `Embarked` with mode.
   - Dropped the `Cabin` column due to excessive nulls.

3. **Encode Categorical Variables**
   - Converted `Sex` using Label Encoding.
   - Used One-Hot Encoding on `Embarked`.

4. **Normalize/Standardize Numerical Features**
   - Standardized `Age` and `Fare` using `StandardScaler`.

5. **Visualize and Remove Outliers**
   - Visualized `Age` outliers using boxplots.
   - Removed outliers using the IQR method.

---

## Output
- Cleaned dataset ready for machine learning models.

---

##  Interview Questions Covered

1. What are the types of missing data?
2. How do you handle categorical variables?
3. Normalization vs Standardization?
4. How to detect outliers?
5. Why is preprocessing important?
6. One-hot encoding vs label encoding?
7. How to handle data imbalance?
8. Can preprocessing affect model accuracy?

---

##  How to Run
1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/data-preprocessing-titanic.git
   cd data-preprocessing-titanic
