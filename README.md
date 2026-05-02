# 🚕 NYC Taxi Data Analysis Project

## 📌 Objective
To analyze the NYC taxi system and determine whether it is functioning normally or showing signs of inefficiency.

---

## 🔢 Act 1: Mathematical Model

Roll number digits:
w = 0, x = 3, y = 1, z = 4

Digital Root:
R = 8

Function:
F(x) = x³/3 - 8x² + 63x

Derivative:
F'(x) = x² - 16x + 63

Critical Points:
x = 7, 9

These values define the range for analysis.

---

## 🧹 Act 2: Data Cleaning

- Removed missing values
- Filtered invalid trips:
  - trip_distance > 0
  - fare_amount > 0

Defined a valid trip as one with consistent and realistic values.

---

## 🧠 Act 3: Behavioral Analysis

Hypothesis:
Longer trips result in higher fares.

Method:
- Correlation between trip_distance and fare_amount

Conclusion:
- Positive relationship observed
- Other factors also influence fare:
  - Traffic conditions
  - Time of day
  - Demand

---

## 📊 Act 4: Pattern Analysis

- Extracted time-based features (hour, date)
- Analyzed:
  - Trips per hour
  - Trips over time

Findings:
- Clear peak hours
- System shows cyclical behavior
- Not purely random

---

## ⚙️ Act 5: Simulation

- Increased fare by 8% (R value)

Observation:
- Average fare increased proportionally
- Indicates system sensitivity to pricing changes

---

## 📈 Act 6: Power BI Dashboard

Visualizations included:
- Trips by Hour (Peak Analysis)
- Trips Over Time
- Distance vs Fare
- Fare Comparison (Simulation)
- Data summary

Additional Insight:
- Highlighted possible misinterpretation and corrected it

---

## 🛠 Tools Used

- Python (Pandas, NumPy, Matplotlib)
- Power BI

---

## ✅ Final Conclusion

The taxi system shows structured and predictable behavior with peak-hour demand.  
While generally stable, it exhibits variations under different conditions, indicating localized inefficiencies rather than system failure.

---

## 📁 Files Included

- Taxi_Project.pbix
- final_output.csv
- act1.py
- analysis code files
