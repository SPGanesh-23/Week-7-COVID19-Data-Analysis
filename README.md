# **COVID-19 Data Analysis & Dashboard System**  
*Exploratory Data Analysis (EDA) and Interactive Dashboard using Kaggle Dataset*

---

## **Overview**

Manual analysis of COVID-19 data is complex, time-consuming, and inefficient. Organizations such as the World Health Organization and research institutions like Johns Hopkins University continuously publish COVID-related datasets across countries, making it difficult to extract meaningful insights without automated analytics.

This project focuses on building a **COVID-19 Data Analysis & Dashboard System** that performs **Exploratory Data Analysis (EDA)** on a real-world Kaggle dataset to understand pandemic trends, identify high-risk countries, and provide interactive visual insights.

By analyzing historical COVID-19 data, the system detects peak periods, growth trends, and relationships between confirmed cases, deaths, and recoveries, helping researchers and organizations make data-driven decisions.

The workflow includes:

- Data Collection: Loading Kaggle COVID-19 dataset
- Data Cleaning: Handling missing values and inconsistencies
- Statistical Analysis: Understanding case distribution
- Trend Analysis: Identifying pandemic waves and peak periods
- Country Comparison: Evaluating affected regions
- Visualization: Interactive charts, heatmaps, and trend graphs
- Dashboard: Interactive Plotly Dash application
- Business Insights: Supporting decision-making with visual analytics

---

## **Dataset**

**Source:** Kaggle  
**Dataset Link:** https://www.kaggle.com/datasets/imdevskp/corona-virus-report  
**Dataset Name:** Corona Virus Report (COVID-19 Dataset)  

**Description:**  
The dataset contains real-world COVID-19 records including observation dates, country/region names, and cumulative counts of confirmed cases, deaths, recoveries, and active cases.

### **Selected Columns**

- Date  
- Country/Region  
- Confirmed  
- Deaths  
- Recovered  
- Active  

### **Removed Columns**

- Province/State  
- Latitude  
- Longitude  
- Last Update  
- Incident Rate  
- Case Fatality Ratio  

The selected columns simplify the dataset and improve dashboard performance.

---

## **Objectives**

1. **Data Collection**
   - Load COVID-19 dataset from Kaggle
   - Select only required columns for analysis

2. **Data Cleaning & Preprocessing**
   - Check missing values
   - Convert Date column into proper datetime format
   - Remove duplicate records
   - Ensure numerical columns are correct

3. **Descriptive Statistics**
   - Total confirmed cases
   - Total deaths
   - Total recoveries
   - Distribution of data

4. **COVID Trend Analysis**
   - Analyze confirmed cases over time
   - Identify peak periods (waves)
   - Study growth trends

5. **Country-Based Analysis**
   - Identify most affected countries
   - Compare countries by confirmed cases, deaths, and recoveries

6. **Dashboard-Based Analysis (Main Focus)**
   - Build interactive dashboard using Plotly Dash
   - Add user controls: country dropdown, date selection
   - Display dynamic charts

7. **Relationship Analysis**
   - Confirmed vs Deaths
   - Confirmed vs Recovered
   - Active vs Confirmed
   - Correlation analysis

8. **Data Visualization**
   - Line charts
   - Bar charts
   - Pie charts
   - Scatter plots
   - Heatmaps

9. **Dashboard Insights**
   - High-risk country identification
   - Recovery trend analysis
   - Pandemic pattern observation

10. **Insights & Conclusion**
    - COVID spread pattern understanding
    - Key trend identification
    - Decision-making support via visual insights

---

## **Project Highlights**

### **1. Data Collection & Cleaning**

- Dataset loaded from Kaggle
- Date column converted into datetime format
- Missing values checked and handled
- Duplicate records removed
- Only relevant columns retained for analysis

This step ensures data reliability and accuracy for downstream analysis.

---

### **2. Exploratory Data Analysis (EDA)**

- Total and average case counts calculated
- Country-wise confirmed, death, and recovery figures analyzed
- Daily and monthly COVID trends examined
- Pandemic wave patterns identified
- Correlations between case metrics explored

EDA helps understand the global spread of COVID-19 and identify the most critical periods and regions.

---

### **3. Visualization**

The project includes:

- **Line Charts** – Confirmed cases and deaths over time
- **Bar Charts** – Top affected countries by case count
- **Pie Charts** – Distribution of confirmed, recovered, and active cases
- **Scatter Plots** – Relationships between case metrics
- **Heatmaps** – Correlation between features

Visualizations make complex pandemic data easy to interpret and understand.

---

### **4. Interactive Dashboard**

Built using **Plotly Dash**, the dashboard provides:

- Country dropdown for region-specific filtering
- Date selection for time-range analysis
- Dynamic charts that update based on user input

The dashboard transforms static analysis into an interactive exploration tool.

---

## **Tools and Technologies**

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Plotly  
- Plotly Dash  
- Jupyter Notebook  
- Google Colab  
- Kaggle Dataset  
- CSV File Storage

---

## **Results**

### **Key Findings**

- **Case Trends:** Confirmed cases show distinct wave patterns across multiple time periods.  
- **Peak Periods:** Certain months recorded significantly higher case and death counts globally.  
- **Most Affected Countries:** A small number of countries account for a large percentage of total confirmed cases.  
- **Recovery Patterns:** Recovery rates improved over time as healthcare responses evolved.  
- **Correlations:** Confirmed cases show strong positive correlation with deaths and recoveries.  
- **Active Cases:** Active case counts reflect the effectiveness of regional containment measures.

---

### **Interpretation**

- **Public Health Response:** Governments can use trend data to time interventions during wave peaks.  
- **Resource Allocation:** High-risk countries can be prioritized for medical resource distribution.  
- **Policy Support:** Recovery and death rate trends inform vaccination and treatment strategies.  
- **Research Use:** Historical patterns support epidemiological modeling and forecasting.  
- **Decision Making:** Automated EDA reduces manual overhead and improves analytical accuracy.

The structured EDA and dashboard approach enhances situational awareness and public health intelligence.

---

## **Conclusion**

The **COVID-19 Data Analysis & Dashboard System** successfully analyzes real-world pandemic data and provides valuable insights for understanding the global spread of COVID-19.

Through structured **EDA and interactive visualization**, the system identifies pandemic waves, country-level impact, and relationships between case metrics, enabling researchers and policymakers to make informed, data-driven decisions.

This project demonstrates how **data analytics and interactive dashboards can transform raw public health data into actionable insights**.

---

## **Author**

**Shree Pranava Ganesh**  
Student at Kamaraj College  
Thoothukudi, Tamil Nadu
