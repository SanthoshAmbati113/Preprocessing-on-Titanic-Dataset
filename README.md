# Preprocessing-on-Titanic-Dataset

This repository contains preprocessing steps applied to the Titanic dataset using Python. The project is structured around cleaning and preparing the data for machine learning tasks.

---

## 🚀 Tasks Completed

1. **Import the Dataset and Explore Basic Info**
   - Loaded Titanic dataset from CSV
   - Explored number of rows, data types, null values using `.info()` and `.isnull().sum()`

2. **Handle Missing Values**
   - Imputed missing `Age` values using median
   - Filled missing `Embarked` values with mode (most frequent value)

3. **Convert Categorical Features into Numerical**
   - Used **one-hot encoding** for `Sex`, `Embarked`, and `Pclass`

4. **Normalize/Standardize Numerical Features**
   - Applied `StandardScaler` from Scikit-learn to:
     - `Age`
     - `Fare`
     - `SibSp`
     - `Parch`

5. **Visualize Outliers and Remove Them**
   - Created **boxplots** for each numerical feature using Seaborn
   - Removed outliers using the **Interquartile Range (IQR) method**

---

## 🛠️ Methods Used

- **One-Hot Encoding**
- **Median/Mode Imputation**
- **Standardization (Z-score normalization)**
- **Boxplot Visualization**
- **IQR Outlier Removal**

---

## 📦 Dependencies

You can install the required libraries using pip:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn

