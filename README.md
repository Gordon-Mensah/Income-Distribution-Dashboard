## 📊 Income Distribution Dashboard

This project provides an exploratory analysis and interactive dashboard for salary data using Python. It helps uncover relationships between income levels and factors like education, gender, age, and occupation.

---

### 🔍 Overview

This notebook performs the following:

- Exploratory Data Analysis (EDA) on the `salary.csv` dataset.
- Visualizations to compare salary distribution based on multiple features.
- An interactive dashboard built using **Dash** and **Plotly**.

The goal is to understand how different attributes influence income (whether someone earns `<=50K` or `>50K` annually).

---

### 📁 Dataset Description

The dataset (`salary.csv`) is derived from the [UCI Adult Income Dataset](https://archive.ics.uci.edu/ml/datasets/adult) and includes the following columns:

| Column            | Description |
|-------------------|-------------|
| `age`             | Age of the individual |
| `workclass`       | Type of employment (e.g., Private, State-gov) |
| `education`       | Highest education level |
| `education-num`   | Education level in numeric form |
| `marital-status`  | Marital status |
| `occupation`      | Job type |
| `relationship`    | Relationship type (e.g., Husband, Wife) |
| `race`            | Race category |
| `sex`             | Gender |
| `capital-gain`    | Capital gains |
| `capital-loss`    | Capital losses |
| `hours-per-week`  | Weekly work hours |
| `native-country`  | Country of origin |
| `salary`          | Target variable (`<=50K`, `>50K`) |

---

### 📌 Key Features

#### 1. **Exploratory Visualizations**
- Age distribution
- Salary by education, gender, and occupation
- Interactive histogram using Plotly

#### 2. **Interactive Dashboard with Dash**
- Dropdown menu to select a feature (e.g., education, gender, occupation)
- Dynamic bar charts comparing salary distributions
- Simple and user-friendly UI

---

### 🚀 Technologies Used

- Python
- Pandas
- Matplotlib
- Seaborn
- Plotly
- Dash (Web-based dashboard)

---

### 📷 Screenshots

You can optionally add screenshots here:
```markdown
https://github.com/Gordon-Mensah/Income-Distribution-Dashboard/blob/main/Images/Age%20Distribution%20by%20Salary.PNG
```

---

### 📦 Installation

If you want to run this project locally:

1. Clone the repository
2. Install the requirements:
```bash
pip install pandas matplotlib seaborn plotly dash
```
3. Run the notebook or the dashboard:
```bash
python salary_dashboard.py
```

---

### 📚 Future Improvements

- Add filtering options (age range, country)
- Create a prediction model to classify income
- Deploy the dashboard online with Heroku or Streamlit

---
## 📄 Additional Report

We’ve added a detailed visual report exploring gender, work, and income patterns from the 1994 Census dataset.  
This PDF includes charts on:

- Salary distribution by gender and occupation
- Average weekly work hours
- Education level breakdown
- Workclass representation by gender

👉 [Click here to view the full PDF report](./Exploring%20Gender%2C%20Work%2C%20and%20Income%20Patterns%20in%20the%201994%20Census.pdf)


### 👨‍💻 Author

**John Jerry Gordon-Mensah**  
