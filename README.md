# 🐞 Bug Dataset Analysis & Cleaning Pipeline

A complete Python-based data cleaning and feature engineering pipeline developed to prepare a software bug tracking dataset containing **50,000 records** for Business Intelligence and data visualization.

This project transforms raw bug tracking data into a clean, structured dataset ready for dashboards in **Power BI**, **Tableau**, or other analytics platforms.

---

# 📌 Project Overview

The objective of this project is to clean, standardize, and enrich a large software bug tracking dataset by applying professional data preprocessing techniques.

The pipeline performs:

- Data exploration
- Missing value handling
- Duplicate removal
- Data standardization
- Feature engineering
- Export of a clean dataset for BI reporting

The final cleaned dataset can be directly used for interactive dashboards and advanced analytics.

---

# 📂 Repository Structure

```
├── Week 2
├── Week 3
├── Week 4
├── Week 5
├── Week 6
├── Week 7
├── Week 8
└── README.md
```

---

# 📊 Dataset Information

The dataset contains **50,000 software bug records** with information such as:

- Bug ID
- Bug Title
- Bug Category
- Bug Domain
- Tech Stack
- Severity
- Environment
- Developer Role
- Root Cause
- Error Code
- Status
- Created Date

Initial Dataset:

- **50,000 Rows**
- **14 Columns**

After Feature Engineering:

- **50,000 Rows**
- **20 Columns**

---

# 🛠️ Data Cleaning Process

## 1. Data Exploration

The pipeline begins with an initial inspection of the dataset.

Performed tasks include:

- Loading the dataset
- Checking data types
- Reviewing dataset shape
- Detecting missing values
- Identifying duplicate records

---

## 2. Missing Value Handling

The dataset contained missing values in the **error_code** column.

These missing numerical values were filled using the **median** of the column to preserve data distribution.

---

## 3. Duplicate Removal

The script checks for:

- Exact duplicate rows
- Duplicate Bug IDs

Any duplicate records are removed to ensure data integrity.

---

## 4. Text Cleaning

All text columns are cleaned by removing:

- Leading spaces
- Trailing spaces
- Extra whitespace

This prevents inconsistent category names during analysis.

---

## 5. Data Standardization

Several categorical columns are converted into a consistent **Title Case** format.

Columns standardized include:

- Bug Category
- Bug Domain
- Tech Stack
- Severity
- Environment
- Developer Role
- Root Cause

The **created_at** column is also converted into a proper datetime format.

---

# ⚙️ Feature Engineering

To support Business Intelligence dashboards, several calculated fields were created.

### Time-Based Features

From the created date:

- Year
- Month
- Quarter
- Day of Week

These fields make time-series analysis much easier.

---

### High Severity Flag

A new column identifies whether a bug has high severity.

Values:

- Yes
- No

---

### Error Code Availability

Another calculated field indicates whether an error code exists.

Values:

- Available
- Missing

---

# 📈 Dashboard Support

The cleaned dataset is optimized for dashboard development.

The repository includes:

- **Dashboard.jpg** – Dashboard overview
- **Dashboard_Screenshots.png** – Interactive dashboard screenshots

These visuals demonstrate how the cleaned data can be used to generate meaningful business insights.

---

# 💾 Output

Running the pipeline generates:

```
Cleaned_Bug_Dataset.csv
```

The exported dataset contains:

- No missing values
- Standardized formatting
- Engineered features
- Clean categorical data
- BI-ready structure

---

# 🚀 Technologies Used

- Python
- Pandas
- NumPy
- Jupyter Notebook

---

# 📦 Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/your-repository.git
```

Move into the project directory:

```bash
cd your-repository
```

Install dependencies:

```bash
pip install pandas numpy
```

---

# ▶️ Run the Project

Using Python:

```bash
python Data_Cleaning.py
```

Or open:

```
Data_Cleaning.ipynb
```

and execute the notebook cells step by step.

---

# 📊 Key Features

✔ Data Exploration

✔ Missing Value Imputation

✔ Duplicate Removal

✔ Text Standardization

✔ Date Formatting

✔ Feature Engineering

✔ BI-Ready Dataset

✔ Dashboard Support

---

# 📚 Learning Outcomes

This project demonstrates practical skills in:

- Data Cleaning
- Data Wrangling
- Feature Engineering
- Exploratory Data Analysis (EDA)
- Python for Data Analytics
- Pandas Data Processing
- Business Intelligence Data Preparation
- Dashboard-Ready Data Modeling

---

# 🤝 Author

**FaaiQ ShieKh**

Aspiring Data Analyst | Python | SQL | Power BI | Excel | Data Visualization

GitHub:
https://github.com/faaiqshiekh05-stack

LinkedIn:
[(Add your LinkedIn profile here)](https://www.linkedin.com/in/faaiq-shiekh-934262299/?lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_view_base%3BRMfChwc9TiaINa2Kk3A%2FgQ%3D%3D)

---

## ⭐ If you found this project helpful, consider giving it a Star!
