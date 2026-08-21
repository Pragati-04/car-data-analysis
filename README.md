# 🚗 Car Dataset Analysis Using Python

## 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA)** on a car dataset containing approximately **11,900 records**. The goal is to analyze car prices, performance, fuel efficiency, and other vehicle characteristics to identify meaningful patterns and relationships.

The analysis focuses particularly on understanding the factors that influence **MSRP (car price)** and the relationship between **engine horsepower, fuel efficiency, and price**.

## 🎯 Objectives

* Identify key factors affecting car prices.
* Analyze the relationship between **Engine HP and MSRP**.
* Study the relationship between **horsepower and fuel efficiency**.
* Compare car manufacturers and their pricing patterns.
* Perform correlation analysis between important numerical features.
* Generate meaningful insights through data visualization.

## 🛠️ Technologies Used

* **Python**
* **Pandas** – Data manipulation and analysis
* **NumPy** – Numerical computations
* **Matplotlib** – Data visualization

## 🧹 Data Cleaning

The following preprocessing steps were performed:

* Removed duplicate records.
* Handled missing values.
* Filled missing **Engine HP** values using the mean.
* Filled missing **Engine Cylinders** using the median.
* Filled missing **Number of Doors** using the mode.
* Checked data types and data consistency.

## 📊 Exploratory Data Analysis

The project includes:

### 1. Summary Statistics

Calculated statistical measures such as mean, median, and standard deviation.

### 2. Car Price Distribution

Analyzed the distribution of MSRP and found that car prices are **right-skewed**, with most cars falling in the lower-to-mid price range and fewer high-end luxury vehicles.

### 3. Top Car Manufacturers

Analyzed manufacturers to identify brands that dominate the dataset.

### 4. Horsepower vs Price

Analyzed the relationship between engine horsepower and MSRP.

**Insight:** Cars with higher horsepower generally tend to have higher prices.

### 5. MPG vs Horsepower

Studied the relationship between fuel efficiency and engine horsepower.

**Insight:** Higher-horsepower cars tend to have lower fuel efficiency.

### 6. Correlation Analysis

Key observations:

* **MSRP** has a positive correlation with **Engine HP**.
* **MPG** has a negative correlation with **Engine HP**.

## 💡 Key Insights

* Engine horsepower is an important factor associated with car pricing.
* Higher-performance vehicles generally have higher MSRPs.
* Increased engine power tends to be associated with lower fuel efficiency.
* Luxury and performance-oriented vehicles contribute to the higher end of the price distribution.

## ⚠️ Limitations

* Missing values may affect the accuracy of the analysis.
* The dataset may not represent current market trends.
* The definition of the popularity metric is unclear.
* External factors such as brand reputation are not fully captured.

## 🔮 Future Scope

The analysis can be extended by using **regression models** and other machine learning techniques to predict car prices and gain deeper insights into the factors influencing MSRP.

## 📁 Project Structure

```text
Car-Dataset-Analysis/
│
├── car_analysis.ipynb
├── data/
│   └── car_data.csv
├── visualizations/
└── README.md
```

> **Note:** Update the filenames and folder structure above according to the actual files in your GitHub repository.

## 👩‍💻 Author

**Pragati Dattatray Mohalkar**

A Python-based data analysis project focused on understanding automotive pricing, performance, and fuel-efficiency patterns through Exploratory Data Analysis.
