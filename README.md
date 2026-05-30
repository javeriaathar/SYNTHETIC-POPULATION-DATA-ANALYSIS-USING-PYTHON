# 📊 Exploratory Data Analysis (EDA) on Synthetic Population Dataset

👉 [Click here to open this project directly in Google Colab](https://google.com)

## 📌 Project Overview
This project demonstrates **Exploratory Data Analysis (EDA)** using Python. A synthetic population dataset is generated containing demographic information such as **Age, Gender, and City**. The dataset is then analyzed to extract meaningful insights through data visualization and statistical methods.

## 🎯 Objective
The main goal of this project is to:
- Create a sample population dataset using Python
- Perform data cleaning and preprocessing
- Analyze demographic patterns
- Visualize distributions using graphs
- Gain insights from structured data

## 🛠️ Tools & Technologies Used
- Python 🐍
- Pandas
- NumPy
- Matplotlib
- Seaborn

## 📂 Dataset Information
The dataset is synthetically generated with the following columns:

| Column | Description |
|--------|-------------|
| ID     | Unique identifier for each record |
| Age    | Age of individuals (1–80 years) |
| Gender | Male / Female |
| City   | Karachi, Lahore, Islamabad, Peshawar |

## ⚙️ Project Workflow

### 1. Data Generation
- Used `NumPy` and `random` to create 1000 records
- Stored data in a CSV file (`population_1000.csv`)

### 2. Data Loading
- Loaded dataset using Pandas
- Displayed basic structure using `.head()`, `.tail()`, `.columns`, `.info()`, and `.describe()`

### 3. Data Cleaning
- Checked missing values
- Identified and removed duplicates

### 4. Data Analysis
- Gender distribution analysis
- Age distribution analysis
- Age comparison across genders

### 5. Data Visualization
- Bar chart for gender distribution
- Histogram for age distribution
- Box plot for age vs gender

## 📊 Visualizations
- 📊 Gender Distribution (Bar Chart)
- 📈 Age Distribution (Histogram)
- 📦 Age Distribution by Gender (Box Plot)

## 📈 Key Insights
- Balanced or near-balanced gender distribution in dataset
- Most individuals fall within a specific age range (based on histogram)
- Gender-based age variation can be observed using box plots
- No missing values or duplicates after cleaning

## 🚀 How to Run This Project

### 1. Clone Repository
```bash
https://github.com/javeriaathar/SYNTHETIC-POPULATION-DATA-ANALYSIS-USING-PYTHON.git
```

### 2. Install Required Libraries
```bash
pip install pandas numpy matplotlib seaborn
```

### 3. Run Python Script / Notebook
```bash
python eda_population.py
```

## 📁 Output Files
- `population_1000.csv` → Raw dataset  
- `clean_population_1000.csv` → Cleaned dataset  

## 💡 Future Improvements
- Add real-world datasets instead of synthetic data
- Include correlation analysis
- Build interactive dashboard using Plotly or Power BI
- Add machine learning predictions

## 👩‍💻 Author
**Javeria Athar**  
Data Analytics 
