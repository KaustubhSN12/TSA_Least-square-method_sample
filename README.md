# TSA_Least-square-method_sample
 
# Least Square Method Mathematical Solution : Link : [Link](https://github.com/KaustubhSN12/TSA_Least-square-method_sample/blob/main/Least%20square%20method.docx)
# Moving Average Report Link : [Link](https://github.com/KaustubhSN12/TSA_Least-square-method_sample/blob/main/MA_Report%20Sample.docx)

# Moving Average Python Solution Link : [Link](https://github.com/KaustubhSN12/TSA_Least-square-method_sample/blob/main/Sample_company_problem_TSA.ipynbx)



# 📊 Time Series Analysis: From Statistical Foundations to Corporate Forecasting

This repository demonstrates the practical application of the **Method of Least Squares** and **Moving Averages** to analyze business performance. It bridges the gap between "pen-and-paper" statistics and automated Python-based data science solutions.

## 📝 Problem Statement

A company needs to evaluate its sales performance over a 24-month period (2024–2025) to identify growth trends and seasonal patterns. The goal is to:

* **Smoothen Volatility:** Use a 3-Month Moving Average to filter out short-term market "noise".
* **Define Growth:** Apply the Method of Least Squares to determine a consistent annual growth trajectory.
* **Strategic Planning:** Provide actionable insights for inventory and marketing optimization.

## 🔢 The Mathematical Foundation

The project begins with a first-principles approach using the straight-line trend equation:


Where  represents the average revenue and  represents the monthly growth rate. For  months, we use a midpoint transformation () to ensure , simplifying the calculation of constants.

### **Key Metrics Summary**

* **Total 2-Year Revenue ():** 4,893,000
* **Average Monthly Revenue ():** 203,875
* **Monthly Growth Rate ():** 7.14 (in scaled units)

## 📈 Visual Insights & Plot Interpretation

The following visualization compares actual sales performance against two distinct statistical models.


![image](https://github.com/KaustubhSN12/TSA_Least-square-method_sample/blob/main/MA.png)

### **Strategic Insights for Stakeholders**

1. **Robust Long-Term Growth:** The red trend line confirms a sustained upward trajectory, indicating that the business is in a consistent expansion phase.
2. **Smoothing Volatility:** The 3-Month Moving Average (green line) reveals that minor dips (e.g., Months 8, 13, and 16) are temporary cyclical fluctuations rather than structural declines.
3. **Cyclical Dips:** Recurring pullbacks every 4–6 months suggest standard procurement cycles or seasonality.

## 🛠️ Implementation Details

The analysis is implemented in Python, mirroring the manual mathematical steps through automation:

* **Data Handling:** `pandas` for Excel processing and rolling window calculations.
* **Calculations:** `numpy` for efficient summation of statistical variables (, ).
* **Visualization:** `matplotlib` for dual-line professional reporting.

## 💡 Business Recommendations

* **Inventory Optimization:** Align staffing and inventory levels with the **Moving Average** line to avoid over-leveraging during temporary spikes.
* **Defensive Marketing:** Launch promotional campaigns 30 days prior to identified "dip" periods to flatten the curve and maintain cash flow.
* **Price Strategy:** Capitalize on the accelerating momentum observed at the end of 2025 to explore price optimizations or upselling opportunities.


