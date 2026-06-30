# 🏥 Hospital Patient Data Analysis using Python

## 📌 Project Overview

This project focuses on analyzing hospital patient data to uncover trends in patient demographics, medical conditions, hospital admissions, billing amounts, and length of stay.
Using Python for data cleaning, feature engineering, and exploratory data analysis (EDA), the project provides meaningful insights that can support healthcare decision-making.

The analysis was performed on a dataset containing over **55,000 patient records**.

---

## 🎯 Objectives

- Perform data cleaning and preprocessing
- Explore patient demographics and healthcare information
- Analyze hospital billing patterns
- Examine admission trends and length of hospital stay
- Visualize key findings using charts
- Generate business insights and recommendations

---

## 📂 Dataset Information

The dataset contains **55,500 patient records** with **15 features**, including:

- Name
- Age
- Gender
- Blood Type
- Medical Condition
- Date of Admission
- Doctor
- Hospital
- Insurance Provider
- Billing Amount
- Room Number
- Admission Type
- Discharge Date
- Medication
- Test Results

---

## 🛠️ Tools & Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

---

## 🧹 Data Cleaning

The following preprocessing steps were performed:

- Checked dataset structure and data types
- Verified missing values
- Checked duplicate records
- Converted admission and discharge dates to datetime format
- Removed 106 records with negative billing amounts
- Created new features:
  - Length of Stay
  - Admission Month
  - Admission Year
  - Age Group

---

## 📊 Exploratory Data Analysis

The following visualizations were created:

- Age Distribution
- Gender Distribution
- Blood Group Distribution
- Medical Condition Distribution
- Admission Type Distribution
- Billing Amount Distribution
- Average Billing Amount by Medical Condition
- Average Billing Amount by Insurance Provider
- Monthly Patient Admissions
- Length of Stay Distribution
- Average Length of Stay by Admission Type
- Correlation Heatmap

---

## 💡 Key Insights

- Patient ages are distributed across a wide range with no dominant age group.
- Male and female patient counts are nearly equal.
- Blood groups are evenly represented in the dataset.
- Cancer has the highest average billing amount among the medical conditions.
- Medicare records the highest average billing amount among insurance providers.
- Patient admissions remain relatively stable throughout the year, with August recording the highest admissions.
- Length of hospital stay ranges from 1 to 30 days with similar averages across admission types.
- No significant correlation exists between age, billing amount, and length of stay.

---

## 📈 Recommendations

- Monitor high-cost medical conditions to identify opportunities for cost optimization.
- Ensure adequate hospital resources during months with relatively higher patient admissions.
- Review billing consistency across insurance providers.
- Continue monitoring patient length of stay to improve hospital resource utilization.
- Incorporate additional clinical variables in future analyses for deeper insights.

---

## 📁 Project Structure

```
Hospital-Patient-Data-Analysis/
│
├── data/
│   └── healthcare_dataset.csv
│
├── notebook/
│   └── Hospital_Patient_Data_Analysis.ipynb
│
└── README.md
```

---

## ▶️ How to Run

1. Clone this repository.
2. Open the notebook in Google Colab or Jupyter Notebook.
3. Install the required libraries if needed.
4. Run all cells sequentially.

---

## 📌 Conclusion

This project demonstrates the complete data analysis workflow, including data cleaning, feature engineering, exploratory data analysis, data visualization,
and business insight generation. It highlights how Python can be used to analyze healthcare data and support data-driven decision-making.

---
