# 🌪️ Tornado Season by the Numbers: A U.S. Analysis (1950–2021)

This project explores patterns and trends in U.S. tornado activity from 1950 to 2021. Using historical data from the National Weather Service, the goal is to uncover when tornadoes are most frequent, how intense they tend to be, and where they strike most often. The analysis combines Python-based data cleaning with visuals in IBM Cognos to deliver clear insights on seasonality, location, and severity.

---

## 🛠️ Tools & Technologies Used

- **Python** (pandas, seaborn, matplotlib)
- **Jupyter Notebook** (data cleaning & analysis)
- **IBM Cognos Analytics** (dashboard + visuals)
- **GitHub** (project version control)
- Dataset: *US Tornado Dataset 1950–2021* (via Kaggle)

---

## 📁 Data Cleaning & Preparation

Data was cleaned in Python before importing into Cognos:

- Renamed columns, standardized casing
- Combined year, month, day into `full_date`
- Mapped month numbers to names
- Filtered invalid rows (e.g., month not between 1–12)
- Grouped and relabeled tornado intensity (F/EF scale)
- Dropped unnecessary coordinate fields
- Exported as `tornado_cleaned.csv`

> A step-by-step cleaning walkthrough is available in [`What to Clean in Python`](#).

---

## 📊 Key Visuals

> *(Visuals displayed in final dashboard — can be shown here as screenshots)*

### 🔷 Tornadoes by Month (Bar Chart)

- **May** has the highest number of tornadoes
- **April** shows a higher **proportion** of strong EF3+ tornadoes

### 📈 Tornadoes by Year (Line Chart)

- General increase in recorded events over time (due in part to better reporting)

### 🌍 Tornadoes by State (US Map)

- Highest activity in **Texas**, **Oklahoma**, **Kansas**, and **Florida**
- Map visual created in IBM Cognos

### 🧱 Tornado Intensity (Stacked Column)

- Most tornadoes are EF0 or EF1
- Strong tornadoes (EF3–EF5) peak in **April and May**

---

## 💡 Insights

- **Tornado season peaks in late spring**, especially in May.
- **April has a higher concentration of powerful tornadoes**, even if total counts are lower than May.
- States in **"Tornado Alley"** and parts of the Southeast are consistently hit hardest.
- Over time, **increased detection and recording** contribute to rising tornado counts.
- A significant portion of tornadoes are **unrated**, which may limit severity analysis in earlier decades.

---

## ✅ Takeaways

This project demonstrates core data analyst skills:

- Finding and cleaning real-world data
- Creating reusable scripts for data wrangling
- Using charts to identify seasonal and geographic trends
- Communicating insights in both code and dashboards

---

## 📌 File Structure

```
📁 tornado-season-project/
│
├── 📄 README.md
├── 📊 tornado_cleaned.csv
├── 📓 tornado_analysis.ipynb
├── 🖼️ dashboard_screenshots/
│   ├── map_chart.png
│   ├── bar_chart.png
│   ├── stacked_chart.png
│   └── pie_chart.png
└── 📁 docs/
    └── what_to_clean_in_python.md
```

---

## 📌 Future Improvements

- Create a Tableau or Power BI version of the dashboard
- Animate month-to-month tornado patterns over time
- Build prediction models (e.g., tornado count by state/month)

---

## 🔗 Links

- [Dataset on Kaggle](https://www.kaggle.com/datasets)
- [Live Dashboard (if published)](https://...)
- [PDF Report (optional)](./docs/final_report.pdf)

---

> **Contact:**\
> *Your Name* – aspiring data analyst in Atlanta, GA\
> [LinkedIn](https://www.linkedin.com/in/your-profile) | [GitHub](https://github.com/your-handle)

