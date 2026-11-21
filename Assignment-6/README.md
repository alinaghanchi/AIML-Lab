# Assignment 6 – Data Preprocessing and Normalization

## 🎯 Aim
To perform data preprocessing and normalization on the Titanic dataset using Python, Pandas, and Scikit-learn.

## 📌 Objectives
- Load and explore the Titanic dataset.
- Identify and handle missing values.
- Encode categorical data into numerical form.
- Normalize numerical features using MinMaxScaler.
- Save the cleaned dataset as a CSV file.

## ⚙️ Steps Performed

1. Imported Pandas and MinMaxScaler.
2. Loaded the Titanic dataset using `pd.read_csv()`.
3. Displayed the first five records using `df.head()`.
4. Checked missing values using `df.isnull().sum()`.
5. Replaced missing Age values with the median.
6. Replaced missing Embarked values with the mode.
7. Removed the Cabin column.
8. Converted Sex values into numerical form:
   - Male = 0
   - Female = 1
9. Applied one-hot encoding to the Embarked column.
10. Normalized Age and Fare using MinMaxScaler.
11. Displayed the cleaned dataset and checked missing values again.
12. Exported the cleaned dataset into a CSV file.

## 📊 Output
The preprocessing operations produce a cleaned Titanic dataset with:
- Missing Age and Embarked values handled.
- Cabin column removed.
- Categorical variables encoded.
- Age and Fare normalized.
- Cleaned data saved as `titanic_cleaned.csv`.

## 📁 Files Included

| File | Description |
|---|---|
| `Assignment_6_AIML.ipynb` | Notebook containing the complete implementation |
| `README.md` | Assignment description and documentation |
