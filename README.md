# 🛫 Airlines Flights Data Analysis — Portfolio Project

This repository showcases an **Exploratory Data Analysis (EDA)** of an airlines flights dataset using Python.  
The goal is to uncover insights on **flight delays, cancellations, carriers, airports, and traffic patterns** through systematic cleaning, analysis, and visualization.

---

## 🚀 Project Overview
- **Load & inspect** raw airline flight data (CSV → pandas DataFrame).  
- **Clean & validate**: datatypes, missing values, timestamps.  
- **Explore**: traffic patterns across months, weekdays, and hours.  
- **Analyze**: delays and cancellations by airline, airport, and time.  
- **Visualize**: correlation heatmaps, scatterplots, bar plots, line plots.  
- **Aggregate**: grouped statistics by carrier, airport, and schedule.  
- **Deliverables**: actionable insights on flight operations and customer impact.  

---

## 🛠 Tech Stack
- **Python** (pandas, numpy)  
- **Visualization**: matplotlib, seaborn  
- **Data Source**: Airlines flights dataset (commonly used in analytics case studies)  

---

## 📊 Results & Takeaways
- **Traffic patterns**: Flight volumes peak during certain months and days-of-week.  
- **Delays**: Specific carriers and airports show consistently higher average delays.  
- **Correlations**: Departure delay strongly impacts arrival delay; cancellations cluster under adverse conditions.  
- **Visual insights**: Heatmaps, line charts, and scatterplots highlighted operational patterns.  

---

## 🧰 Functions & Methods Used
### Data Loading & Cleaning
- `pd.read_csv()`, `pd.to_datetime()`, `df.info()`, `df.isnull()`  

### Exploration
- `df.head()`, `df.nunique()`, `df.value_counts()`, `df.corr()`  

### Aggregation & Grouping
- `groupby()`, `sum()`, `mean()`, `max()`  

### Visualization
- `df.plot(kind=...)`, `plt.figure()`, `plt.show()`  
- `sns.heatmap()`, `sns.barplot()`, `sns.lineplot()`, `sns.scatterplot()`  
