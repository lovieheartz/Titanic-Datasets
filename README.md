# Task 1: Data Cleaning & Preprocessing

## Objective
Clean and prepare raw data for machine learning by handling missing values, encoding categorical features, scaling numerical data, and detecting/removing outliers.

---

##  Dataset Used
**Titanic Dataset**  
[Kaggle Link](https://www.kaggle.com/datasets/yasserh/titanic-dataset)

---

## Tools & Libraries
- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Scikit-learn

---

##  Steps Performed

1. **Loaded and explored the dataset**
   - Viewed structure, data types, and missing values.

2. **Handled missing values**
   - Filled `Age` with median.
   - Filled `Embarked` with mode.
   - Dropped `Cabin` due to high missing percentage.

3. **Encoded categorical variables**
   - Applied one-hot encoding to `Sex` and `Embarked`.

4. **Scaled numerical features**
   - Standardized `Age` and `Fare` using `StandardScaler`.

5. **Detected and removed outliers**
   - Visualized using boxplots.
   - Removed top 5% extreme values in `Fare`.

6. **Saved cleaned dataset**
   - Exported as `titanic_cleaned.csv`.

---

##  Files in This Repo

- `Titanic_Data.ipynb`: Notebook with complete preprocessing steps.
- `Titanic_cleaned.csv`: Final cleaned dataset.
- `README.md`: Project overview and instructions.
- `requirements.txt`: Python dependencies.

---

##  How to Run

1. Clone this repository:
   ```bash
   git clone <repo-url>
   cd <repo-folder>
