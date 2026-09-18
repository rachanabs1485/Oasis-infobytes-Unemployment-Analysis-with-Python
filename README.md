# 📊 Unemployment Analysis with Python

## 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA)** on unemployment data in India to identify regional and temporal trends. The analysis focuses on unemployment rates, employment levels, labour participation rates, and changes observed during the COVID-19 period.

## 🎯 Objective

The main objectives of this project are to:

* Analyze unemployment rates across different regions of India.
* Identify monthly and temporal unemployment trends.
* Compare unemployment rates across major states.
* Find the top 10 regions with the highest average unemployment rates.
* Analyze correlations between unemployment, employment, and labour participation.
* Compare Pre-COVID and Post-COVID unemployment patterns.
* Create meaningful visualizations to communicate the findings.

## 🛠️ Technologies Used

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**
* **Google Colab / Jupyter Notebook**

## 📂 Dataset

The project uses the **Unemployment in India** dataset, publicly available on Kaggle.

Dataset: [Unemployment in India – Kaggle](https://www.kaggle.com/datasets/gokulrajkmv/unemployment-in-india)

The dataset contains information such as:

* Region
* Date
* Estimated Unemployment Rate (%)
* Estimated Employed
* Estimated Labour Participation Rate (%)

## 🔍 Analysis Performed

### 1. Data Loading & Cleaning

* Loaded the Kaggle dataset using Pandas.
* Inspected dataset shape and columns.
* Checked for missing values.
* Converted the date column to datetime format.
* Converted numerical columns to appropriate data types.
* Removed unnecessary columns and handled missing values.

### 2. Region-wise Analysis

Calculated the average unemployment rate for each region and visualized the differences using a bar chart.

### 3. Monthly Trend Analysis

Analyzed unemployment rates over time using a time-series line chart to identify monthly changes and trends.

### 4. Major State Comparison

Compared unemployment trends across selected major states using time-series visualization.

### 5. Top 10 Regions

Identified and visualized the 10 regions with the highest average unemployment rates.

### 6. Correlation Analysis

Created a correlation heatmap to examine relationships between:

* Unemployment Rate
* Estimated Employed
* Labour Participation Rate

Correlation represents statistical association and does not establish causation.

### 7. Pre-COVID vs Post-COVID Analysis

Divided the dataset into Pre-COVID and Post-COVID periods and compared average:

* Unemployment Rate
* Estimated Employed
* Labour Participation Rate

## 📈 Key Visualizations

The notebook includes:

* 📊 Region-wise average unemployment bar chart
* 📈 Monthly unemployment trend line chart
* 📉 State-wise time-series comparison
* 🏆 Top 10 regions bar chart
* 🔥 Correlation heatmap
* 🦠 Pre-COVID vs Post-COVID comparison

## 💡 Key Insights

The analysis highlights differences in unemployment rates across Indian regions and shows how unemployment changed over time. The COVID-19 period represents a notable change in the unemployment trend, while regional comparisons demonstrate that labour-market conditions varied across different parts of India.

## 📁 Project Structure

```text
Unemployment-Analysis-Python/
│
├── Unemployment_Analysis.ipynb
├── cleaned_unemployment_india.csv
└── README.md
```

## 🚀 How to Run

1. Download or clone this repository.
2. Open `Unemployment_Analysis.ipynb` in **Google Colab** or Jupyter Notebook.
3. Download the dataset from Kaggle.
4. Upload the dataset to Google Colab if required.
5. Run the notebook cells sequentially.
6. View the generated tables, charts, and analysis.

## 👩‍💻 Author

**Rachana B S**

B.E. Information Science & Engineering
Interested in **Data Science, AI/ML, Generative AI, and Data Analytics**.
