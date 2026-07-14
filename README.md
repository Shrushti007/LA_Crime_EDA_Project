# LA_Crime_EDA_Project
An Exploratory Data Analysis (EDA) project on Los Angeles crime data using Python, Pandas, Matplotlib, and Seaborn to uncover crime trends, hotspots, victim demographics, temporal patterns, and actionable insights through data visualization.


## 📌 Project Overview

Crime data contains valuable insights that can help law enforcement agencies, policymakers, and communities better understand criminal activities and improve public safety measures.

This project performs a comprehensive Exploratory Data Analysis (EDA) on over **1 million crime records** reported by the **Los Angeles Police Department (LAPD)** to identify:

- Crime trends over time
- High-risk geographic areas
- Victim demographic patterns
- Temporal crime behavior
- Weapon involvement
- Crime resolution patterns
- Actionable recommendations for crime prevention

---

## 🎯 Project Objectives

The objectives of this project are to:

- Analyze yearly and monthly crime trends.
- Identify the most common crime categories.
- Detect crime hotspots across Los Angeles.
- Study victim demographics such as age, gender, and descent.
- Investigate crime patterns by hour, weekday, and season.
- Examine weapon involvement in criminal incidents.
- Provide prescriptive insights for improving public safety.

---

## 📂 Dataset Information

| Attribute | Value |
|-----------|-------|
| Dataset Name | Crime Data from 2020 to Present |
| Source | Los Angeles Police Department (LAPD) |
| Records | 1,005,198 |
| Features | 28 |
| Dataset Type | Structured Tabular Data |

Each row in the dataset represents **one reported crime incident**.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 🧹 Data Cleaning & Preprocessing

The following preprocessing steps were performed before analysis:

### ✔ Missing Value Analysis
- Identified missing values and their percentages.
- Examined columns with high null percentages.

### ✔ Duplicate Handling
- Checked duplicate case numbers (`DR_NO`).
- Verified complete row duplication.

### ✔ Datetime Conversion
Converted:

- `Date Rptd`
- `DATE OCC`

into proper datetime format.

### ✔ Feature Engineering

Created additional temporal features:

- Year OCC
- Month OCC
- Weekday OCC
- Hour OCC

### ✔ Victim Demographic Cleaning

Standardized:

- Victim Sex
- Victim Descent

Handled unknown and invalid values.

### ✔ Geographic Cleaning

Removed invalid coordinates:

- `(LAT, LON) = (0,0)`

which represent non-geocoded incidents.

---

# 📊 Exploratory Data Analysis

---

## 🟢 Amateur Questions (Descriptive Analytics)
### Focus: **What happened?**

| Question | Visualization |
|----------|--------------|
| How many crime incidents are recorded? | Summary Statistics |
| Which are the top 10 crime types? | Horizontal Bar Chart |
| Which age groups are most affected? | Histogram |
| Which weekdays have the highest crime rates? | Bar Chart |
| At what hour do most crimes occur? | Bar Chart |
| Which areas report the highest crime rates? | Horizontal Bar Chart |

---

## 🟡 Professional Questions (Diagnostic Analytics)
### Focus: **Why did it happen?**

| Question | Visualization |
|----------|--------------|
| Has crime increased or decreased over the years? | Line Chart |
| Which crime types are increasing the fastest? | Multi-Line Chart |
| Are weekends more dangerous than weekdays? | Bar Chart |
| Which areas are associated with specific crime types? | Heatmap |
| Are certain age groups affected by specific crimes? | Stacked Bar Chart |
| Are weapons associated with particular crimes? | Heatmap |


---

## 🔴 Master-Level Questions (Predictive & Prescriptive Analytics)
### Focus: **What is likely to happen and what should we do?**

| Question | Visualization |
|----------|--------------|
| Can we predict future crime hotspots? | Geographic Heatmap |
| What factors contribute most to crime occurrence? | Correlation Heatmap |


---

## 📈 Key Visualizations

This project includes:

- 📈 Crime Trends by Year
- 🚔 Top 10 Crime Categories
- 🌍 Crime Hotspots
- 👥 Victim Age Distribution
- 🕒 Crimes by Hour
- 📅 Crimes by Weekday
- 🏙️ Area-wise Crime Analysis
- 🔫 Weapon Usage Analysis
- 🔥 Crime Type vs Area Heatmap
- 📊 Weapon vs Crime Heatmap
- 📉 Correlation Analysis

---

## 🔍 Key Insights

- Crime incidents exhibit clear temporal and geographic patterns.
- Crime rates vary significantly by hour and weekday.
- Certain police divisions consistently report higher crime volumes.
- Young adults constitute the largest victim demographic.
- Property crimes dominate the dataset.
- Public spaces and residential locations account for most incidents.
- Weapon involvement is concentrated in specific crime categories.

---

## 💡 Prescriptive Recommendations

Based on the analysis, the following recommendations can be made:

- Increase police deployment in hotspot regions.
- Improve street lighting in high-risk locations.
- Install additional CCTV surveillance systems.
- Increase patrol frequency during peak crime hours.
- Conduct awareness campaigns for vulnerable groups.
- Develop area-specific crime prevention strategies.
- Implement predictive policing models for proactive intervention.

---

## 📁 Project Structure

```text
LA_Crime_EDA_Project/
│
├── data/
│   ├── Crime_Data_from_2020_to_Present.csv
│   └── LA_Crime_Data_Cleaned.csv
│
├── notebooks/
│   └── LA_CrimeEDA_Project.ipynb
│
├── images/
│   ├── crime_trend_year.png
│   ├── top_crime_types.png
│   ├── crime_hotspots.png
│   ├── victim_age_distribution.png
│   ├── crimes_by_hour.png
│   ├── crimes_by_weekday.png
│   ├── area_wise_crime.png
│   └── weapon_usage.png
│
├── README.md
└── requirements.txt
```

---

## 🚀 Future Scope

- Build machine learning models for crime prediction.
- Develop interactive dashboards using Streamlit or Power BI.
- Apply clustering techniques for hotspot identification.
- Forecast future crime trends using time-series models.
- Integrate Generative AI for automated crime intelligence reporting.

---

## 🤝 Contributions

Contributions, suggestions, and improvements are welcome.

Feel free to fork the repository and submit a pull request.

---

## 📜 License

This project is intended for educational and portfolio purposes only.

---

## ⭐ If you found this project useful, consider giving it a star on GitHub!
