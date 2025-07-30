# Electricity_Consumption

# 🔌 City Power Consumption Analysis

This project explores a city’s power consumption dataset to uncover patterns and relationships among environmental factors such as temperature, humidity, wind speed, and cloudiness. The goal is to extract insights that help in understanding how external factors influence power usage.

---

## 📊 Key Features

- **Exploratory Data Analysis (EDA)**:
  - Descriptive statistics
  - Handling missing values
  - Data cleaning and formatting

- **Visualizations**:
  - Distribution plots for each numerical feature
  - Correlation heatmaps
  - Pairwise scatter plots
  - Boxplots for outlier detection

- **Outlier Analysis**:
  - Identified outliers using visual and statistical methods (IQR/Z-score)
  - Investigated impact on power consumption

- **Insights**:
  - Investigated the relationship between cloudiness and power usage
  - Identified variables with strong or weak correlations to power consumption

---

## 📂 Dataset Description

The dataset contains the following key columns:

| Column        | Description                                |
|---------------|--------------------------------------------|
| Temperature   | City temperature during measurement        |
| Humidity      | Relative humidity percentage               |
| Wind Speed    | Speed of wind in the city                  |
| Cloudiness    | Cloud cover (%)                            |
| Power Consumption | Power consumed in the city (in kWh)     |

> 📝 Note: The dataset does **not** include timestamp or zone/location columns.

---

## 🧰 Tools & Technologies

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
