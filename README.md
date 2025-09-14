# Data Science Internship - Task 2 (Titanic Dataset Analysis)

This project is part of the **Maincrafts Data Science with Python Internship**.

## Task Description
In this task, we analyze the famous **Titanic dataset** to explore survival patterns and practice data cleaning and visualization skills.

### Requirements from Task PDF
1. Load the Titanic dataset.
2. Clean data (handle missing values like `Age` and `Embarked`).
3. Answer questions:
   - Who survived more: males or females?
   - Did passenger class affect survival chances?
   - What was the survival rate by age group?
4. Visualize results using Seaborn / Matplotlib:
   - Bar chart of survival by gender.
   - Bar chart of survival by class.
   - Histogram of passenger ages.

---

## Tools & Libraries
- Python
- Pandas
- Matplotlib
- Seaborn

---

## Steps Implemented
1. **Load dataset** (`train_and_test2.csv`).
2. **Data Cleaning**: Filled missing values in `Age` (median) and `Embarked` (mode).
3. **Analysis & Visualization**:
   - Bar chart: Survival by **Gender**.
   - Bar chart: Survival by **Passenger Class**.
   - Bar chart: Survival by **Age Groups** (Child, Teen, Adult, Senior).
   - Histogram: **Passenger Age Distribution**.

---

## Insights
- **Females survived more than males**.
- **1st Class passengers** had higher survival chances compared to 2nd and 3rd class.
- **Children** had relatively higher survival rates than adults/seniors.
- Most passengers were **young adults (20-40 years old)**.

---

## Files in Repository
- `maincrafts_task2_cleaned.ipynb` → Jupyter Notebook with full analysis & plots.
- `train_and_test2.csv` → Titanic dataset used.
- `README.md` → Project overview.
