# 🛣️ Road Accident Analysis: Identifying Major Causes via Data Science  
**Repository:** Data_science_project_1  
**Author:** S. Hitesh Borha  
**Domain:** Data Science • Exploratory Data Analysis • Predictive Modeling  
**Date:** June 2025  

---

## 📘 Project Overview  
Road accidents continue to pose a significant public‑safety challenge worldwide. This project uses real‑world accident data to **identify major contributing factors**, **explore key feature relationships**, and build a **predictive model** to highlight high‑risk scenarios. The goal is to derive actionable insights that can inform policy, traffic planning, and safety measures.

---

## 🚨 Problem Statement  
- With large volumes of traffic data available, simply plotting counts is insufficient for deeper insights.  
- Many accident‑analysis efforts don’t explore relationships between environmental, vehicular, temporal and human‑factors.  
- Predictive modeling remains under‑utilised in public datasets for accident causation and risk identification.

---

## 🎯 Project Objectives  
- Clean and preprocess an open‑source road‑accident dataset.  
- Perform exploratory data analysis (EDA) to uncover patterns (e.g., time of day, weather conditions, road types).  
- Apply feature‑engineering and statistical visualization to identify key accident‑causing variables.  
- Build a predictive model (or multiple models) to flag high‑risk accident scenarios.  
- Generate insights that can support traffic‑safety stakeholders (policymakers, planners, enforcement agencies).

---

## 🧩 Methodology  

### 1. Data Collection & Preprocessing  
- Load the raw dataset (e.g., `cleaned.csv`).  
- Handle missing values, outliers, and inconsistent formats.  
- Transform categorical variables, normalize numeric features.

### 2. Exploratory Data Analysis (EDA)  
- Visualize the distribution of accidents by hour, road type, weather, vehicle type.  
- Use correlation heatmaps to identify relationships between features.  
- Highlight top contributing factors using bar charts, pie charts, and scatter plots.

### 3. Feature Engineering & Selection  
- Create derived features (e.g., “Night vs Day”, “Weekday vs Weekend”).  
- Use statistical techniques (e.g., train/test split, feature importance) to select top predictors.

### 4. Model Building & Evaluation  
- Apply machine‑learning models (for example: logistic regression, decision tree, random forest) in R.  
- Evaluate using metrics like Accuracy, Precision, Recall, F1‑Score, ROC‑AUC.  
- Compare model performance and choose the best performing one.

---

## 📊 Key Findings (Example)  
- Accident frequency peaks between **5 PM–8 PM** and on **weekends**.  
- Road segments with **poor lighting** or **wet weather** show significantly higher risk.  
- Certain vehicle types (e.g., heavy trucks) and road‑types (e.g., highways with high speeds) contribute disproportionately.  
- The final predictive model achieved an **F1‑Score of ~0.82** (example value – replace with your actual result) and reliably flagged high‑risk scenarios.

---

## 🧰 Tech Stack  
- **Programming Language:** R  
- **Main Script:** `Road_Accidents.R`  
- **Dataset:** `cleaned.csv` (pre‑processed)  
- **Libraries:**  
  - Data manipulation: `dplyr`, `tidyr`  
  - Visualization: `ggplot2`, `plotly`  
  - Modeling: `caret` (or other)  

### Repository Structure:
```
├── Road_Accidents.R         # main analysis & model script  
├── cleaned.csv              # processed dataset  
├── .gitignore  
└── README.md                # this file  
```

---

## 📚 How to Run  
1. Clone the repository:  
   ```bash
   git clone https://github.com/hitesh114/Data_science_project_1.git
   ```  
2. Open **Road_Accidents.R** in RStudio (or another R environment).  
3. Ensure required packages are installed (e.g., `install.packages("dplyr")`, etc.).  
4. Run the script end‑to‑end or step‑by‑step for EDA, modeling, results.  
5. Review generated visualizations and model output.

---

## 🚀 Future Work  
- Extend dataset with **geospatial data** (latitude/longitude) for mapping accident hotspots.  
- Incorporate **time‑series modeling** to forecast accident trends.  
- Integrate this model into a **real‑time dashboard** for traffic‑safety monitoring.  
- Expand to multi‑region or global datasets to validate generalizability.

---

## 💡 Acknowledgments  
Thanks to [Insert data source name, e.g., Government Road Safety Agency] for providing the accident dataset.  
Thanks to [any mentors, colleagues] for guidance and feedback.

---

## 🧷 Keywords  
`Road Accident` • `Data Science` • `Exploratory Data Analysis` • `Predictive Modeling` • `R Programming` • `Traffic Safety`
