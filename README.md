# Bellabeat Case Study: Data-Driven Marketing Insights

## 📌 Overview
This project is part of the **Google Data Analytics Professional Certificate** capstone, where I applied data analysis skills to generate marketing insights for **Bellabeat**, a high-tech wellness company.

As a Junior Data Analyst, my goal was to analyze smart device usage data to:
- Discover user behavior patterns related to activity, sleep, and calories.
- Provide actionable marketing recommendations for the **Bellabeat Leaf** product.

---

## 🔎 Business Task
Bellabeat wants to leverage insights from smart device data to enhance its marketing strategy, focusing on:
- Activity trends
- Sleep patterns
- User engagement opportunities

---

## 🗂️ Datasets Used
- `dailyActivity_merged.csv` - Daily steps, calories, activity minutes.
- `hourlySteps_merged.csv` - Hourly step counts.
- `sleepDay_merged.csv` - Sleep duration and efficiency.

*Source:* Public Fitbit Tracker Data on [Kaggle](https://www.kaggle.com/datasets/arashnic/fitbit)

---

## 🛠️ Tools & Technologies
- **RStudio**
- **Microsoft Excel:** for cleaning & quick look of database 
- **R Programming:** tidyverse, dplyr, ggplot2, tidyr
- **RMarkdown** for documentation and reporting

---

## 📈 Key Findings
- Users average around 8,500 steps/day, burning approximately 2,300 calories/day. More steps correspond to more calories burned
- Only 32% Users sleep around 7 hours on average. Longer and more consistent sleep is often seen in users with higher daily step counts.
- Users are most active at 6-7 PM.
- There is a positive but modest correlation between daily steps and sleep duration, suggesting active users tend to sleep slightly better.

---

## 📢 Marketing Recommendations
1. Promoting morning and evening routines when users are most active.  
2. Introducing weekend challenges to boost engagement during lower activity periods.  
3. Using personalized notifications to encourage daily step goals that contribute to better sleep.  
4. Creating data-backed educational content highlighting the link between movement, sleep, and overall wellness.

---

## 📎 Output Files
- [RMarkdown File (.Rmd)](link-to-your-Rmd)
- [HTML Report](link-to-your-html)
- [PowerPoint Presentation](link-to-your-pdf)

---

## 🚀 How to Run This Project
1. Clone this repository.
2. Open the `.Rmd` file in RStudio.
3. Install required packages:
```r
install.packages(c("dplyr", "ggplot2", "tidyr", "readr"))
