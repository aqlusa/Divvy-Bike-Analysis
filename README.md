# Divvy Bike Share Analysis

This project analyzes 12 months of Divvy bike-sharing data to identify usage patterns between **casual riders** and **annual members**. The goal is to uncover insights that can help inform business decisions for improving customer experience and operations.

## 📊 Objectives
- Compare ride behaviors between casual and member riders
- Analyze average ride lengths by user type, day of week, and month
- Present insights visually using R

## 🧰 Tools & Packages Used
- **R** & **R Markdown**
- `tidyverse`: data cleaning and wrangling
- `lubridate`: date and time manipulation
- `ggplot2`: data visualization

## 🔍 Key Steps in Analysis
1. **Data Wrangling**  
   Combined 12 months of CSV data, removed nulls and duplicates, filtered out test entries.

2. **Feature Engineering**  
   Created new variables: `ride_length`, `day_of_week`, `month`.

3. **Descriptive Analysis**  
   Summarized ride statistics by user type, day, and month.

4. **Visualization**  
   Plotted average ride lengths and ride counts to compare usage patterns.

## 📈 Summary of Findings
- **Casual riders** generally have longer ride durations than members.
- Members ride more consistently throughout the week, while casual riders peak during weekends.
- There are seasonal trends in ride volume, with the highest usage in summer months.

## 📂 Project Files
- `avg_ride_length.Rmd`: Full R Markdown script used for the analysis
- `README.md`: This file
- `/output`: [avg_ride_length.html](https://d1a91e08be124c03bb3e95801471e079.app.posit.cloud/file_show?path=%2Fcloud%2Fproject%2Favg_ride_length.html)

## 🔗 How to Run
Open `avg_ride_length.Rmd` in RStudio and knit the document to view the full analysis.

---

> 🚴‍♀️ This project was completed as part of the [Google Data Analytics Professional Certificate](https://www.coursera.org/professional-certificates/google-data-analytics), showcasing practical skills in real-world data cleaning, analysis, and visualization.
