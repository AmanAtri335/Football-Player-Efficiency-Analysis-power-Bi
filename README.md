# ⚽ Football Player Efficiency Analysis | Power BI

![Dashboard Overview](Assets/Dashboard_Overview.png)

## 📌 Project Overview

Traditional football analysis often focuses on one question:

> **Who scored the most goals?**

While total goals are important, they don't always reflect true player performance.

This project takes a different approach by analyzing **Goals per Game (GPG)** to evaluate scoring efficiency rather than scoring volume.

By comparing two groups of players, the analysis demonstrates how relying solely on raw totals can lead to misleading conclusions and poor decision-making.

---

## 🎯 Objective

The primary objectives of this project are:

* Evaluate player performance using **Goals per Game (Efficiency)**.
* Compare scoring efficiency between **Group A** and **Group B** players.
* Identify whether higher goal totals indicate better performance.
* Demonstrate the importance of normalized metrics in sports analytics.
* Showcase how data storytelling can reveal hidden insights.

---

## ❓ Business Problem

Football clubs, scouts, and analysts often evaluate players based on cumulative statistics such as:

* Total Goals
* Total Appearances
* Total Assists

However, these metrics may not accurately reflect player quality.

This project addresses the following questions:

* Is the player with more goals always the better performer?
* Which player group converts appearances into goals more efficiently?
* Can efficiency metrics reveal insights hidden behind raw totals?
* How can data-driven analysis improve player evaluation?

---

## 🛠️ Methodology

### Data Preparation

* Cleaned and structured player performance data.
* Standardized statistical fields.
* Calculated efficiency-based performance metrics.

### KPI Development

#### Performance Metrics

* Total Goals
* Total Appearances
* Goals per Game (GPG)

#### Comparative Metrics

* Group A Efficiency
* Group B Efficiency
* Efficiency Difference

### Dashboard Design

Created an interactive Power BI dashboard to:

* Compare player groups
* Analyze scoring efficiency
* Visualize performance trends
* Support data-driven decision making

---

## 📊 Key Insight

Although **Group B** players score more goals overall, they are less efficient than **Group A**.

| Group   | Goals per Game |
| ------- | -------------- |
| Group A | 0.51           |
| Group B | 0.34           |

### Conclusion

> **More Output ≠ Better Performance**

Efficiency provides a more meaningful measure of player effectiveness than raw totals alone.

---

# 📸 Dashboard Preview

## 1️⃣ Executive Dashboard

![Dashboard Overview](Assets/Dashboard_Overview.png)

This dashboard provides an overall view of player performance, efficiency metrics, and comparative analysis.

---

## 2️⃣ Efficiency Comparison Analysis

![Efficiency Analysis](Assets/Efficiency_Analysis.png)

### Insights

* Clear performance gap between player groups.
* Group A consistently demonstrates higher scoring efficiency.
* Highlights the importance of normalized metrics.

### Business Value

Decision-makers can identify high-performing players who may be overlooked when evaluating only total goals.

---

## 3️⃣ Appearances vs Goals per Game

![Scatter Plot](Assets/Appearances_vs_GPG.png)

### Insights

* Visualizes relationship between appearances and scoring efficiency.
* Slight downward trend observed.
* Suggests efficiency may decline as appearances increase.

Possible factors include:

* Fatigue
* Tactical role changes
* Team dynamics

### Business Value

Provides deeper context beyond simple scoring statistics.

---

## 🔍 Key Findings

### Raw Metrics Can Be Misleading

Players with the highest goal totals are not always the most efficient performers.

### Efficiency Metrics Matter

Goals per Game provides a fair comparison across players with different numbers of appearances.

### More Data Does Not Guarantee Better Insights

Choosing the wrong metric can lead to incorrect conclusions.

### Data Storytelling Creates Impact

The same dataset can reveal completely different insights depending on how it is analyzed.

---

## 🧰 Tools & Technologies

| Tool                 | Purpose                               |
| -------------------- | ------------------------------------- |
| Power BI             | Dashboard Development & Visualization |
| Power Query          | Data Cleaning & Transformation        |
| DAX                  | KPI Calculations                      |
| Excel / CSV          | Dataset Storage                       |
| Statistical Analysis | Efficiency & Comparative Metrics      |

---

## 📂 Project Structure

```text
Football-Player-Efficiency-Analysis/
│
├── Assets/
│   ├── Dashboard_Overview.png
│   ├── Efficiency_Analysis.png
│   ├── Appearances_vs_GPG.png
│   └── Data_Model.png
│
├── Power BI File/
│   └── Football_Player_Efficiency.pbix
│
├── Data Source.md
├── Insights.md
│
└── README.md
```

---

## 🚀 How to Use

### Step 1

Download the Power BI file from the repository.

### Step 2

Open the `.pbix` file using Power BI Desktop.

### Step 3

Explore:

* Player-level performance metrics
* Group comparisons
* Efficiency analysis
* Interactive dashboard filters

---

## 📚 Dataset Information

The dataset contains historical football player performance statistics including:

* Player Appearances
* Goals Scored
* Goals per Game
* Player Group Classification

The data was prepared specifically to support efficiency-based performance analysis.

---

## 💡 Key Learnings

* Total goals alone do not represent player quality.
* Goals per Game provides a more accurate performance measure.
* Normalized metrics improve decision-making.
* Effective visual storytelling can uncover hidden insights.
* Data analysis should focus on meaningful metrics rather than volume alone.

---

## 🚀 Future Improvements

### Advanced Football Metrics

* Expected Goals (xG)
* Expected Assists (xA)
* Shot Conversion Rate
* Player Contribution Index

### Advanced Analytics

* Player Segmentation using Clustering
* Predictive Performance Modeling
* Multi-League Comparison
* Season-over-Season Analysis

---

## 💼 Business Value

This project demonstrates how analytics can challenge traditional assumptions and provide deeper insights into performance.

The same principle extends beyond football to any industry where productivity, efficiency, and outcomes must be evaluated relative to effort and opportunity.

By focusing on efficiency rather than volume, organizations can make smarter and more objective decisions.

---

## 👨‍💻 Author

**Aman Atri**

Aspiring Data Analyst | Power BI | SQL | AI & Data Analytics

⭐ If you found this project useful, consider starring the repository.
