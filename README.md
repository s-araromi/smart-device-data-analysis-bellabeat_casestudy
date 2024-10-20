# **Bellabeat Case Study: Smart Device Data Analysis**

## **Project Overview**
This project focuses on analyzing smart device data for Bellabeat, a high-tech wellness company that develops products for women's health. The objective of this case study is to analyze Fitbit data and uncover trends in user behavior—such as physical activity, sleep patterns, and calorie expenditure—that will inform Bellabeat’s marketing strategy and product recommendations.

The analysis provides insights into daily steps, sleep habits, calories burned, and correlations with weight and activity levels. These insights are crucial for helping Bellabeat target its users with personalized health and wellness campaigns, thereby enhancing engagement and promoting product usage.

## **Business Task**
Bellabeat is looking to expand its market share in the global smart device industry. The goal of the project is to:
- Identify trends in smart device usage (such as activity and sleep patterns).
- Apply these trends to Bellabeat's products.
- Provide recommendations on how Bellabeat can refine its marketing strategy to increase user engagement.

## **Data Source**
The data used in this project is derived from a publicly available Fitbit dataset, which includes:
- Daily activity data: Steps taken, calories burned, and activity intensity.
- Sleep data: Total minutes asleep and total time in bed.
- Weight logs: Users' weights and correlations with daily steps.

The dataset consists of personal fitness tracker data from 30 Fitbit users.

## **Repository Structure**
The repository is organized into the following structure:

```
bellabeat-case-study/
│
├── data/
│   ├── dailyActivity_merged.csv
│   ├── hourlyCalories_merged.csv
│   ├── hourlyIntensities_merged.csv
│   ├── sleepDay_merged.csv
│   ├── weightLogInfo_merged.csv
│
├── visualizations/
│   ├── total_steps_vs_calories.png
│   ├── activity_intensity_vs_calories_burned.png
│   ├── sleep_vs_time_in_bed.png
│   ├── weight_vs_steps.png
│   ├── steps_vs_sleep_quality.png
│
├── notebooks/
│   ├── bellabeat-casestudy.ipynb
│   
│
├── reports/
│   └── Bellabeat Smart Device Data Analysis Report.pdf
│
└── README.md
```

### **Files and Folders to Upload**
1. **Data Folder** (`/data/`):
   - Contains all the necessary data files used in the analysis, such as:
     - `dailyActivity_merged.csv`: Data on daily steps, distance, and calories burned.
     - `hourlyCalories_merged.csv`: Hourly data on calories burned.
     - `hourlyIntensities_merged.csv`: Hourly data on activity intensity.
     - `sleepDay_merged.csv`: Sleep data, including time asleep and time in bed.
     - `weightLogInfo_merged.csv`: User weight logs.

2. **Visualizations Folder** (`/visualizations/`):
   - Contains visualizations generated from the analysis:
     - `total_steps_vs_calories.png`: Visualization showing the relationship between steps and calories burned.
     - `activity_intensity_vs_calories_burned.png`: Visualization of activity intensity versus calories burned.
     - `sleep_vs_time_in_bed.png`: Visualization comparing total time in bed with total minutes asleep.
     - `weight_vs_steps.png`: Scatter plot of weight versus total steps.
     - `steps_vs_sleep_quality.png`: Scatter plot of total steps versus sleep quality.

3. **Notebooks Folder** (`bellabeat-casestudy.ipynb`):
   - Contains the R Markdown and rendered HTML of the analysis:
     - `bellabeat-casestudy.ipynb`: The R Markdown file used to run the data analysis.
   

4. **Reports Folder** (`Bellabeat Smart Device Data Analysis Report.pdf`):
   - Contains the final report summarizing the entire case study, including visualizations and key insights:


## **Analysis Overview**
### **Steps Involved in the Analysis**
The data analysis was conducted using the following steps:
1. **Data Preparation**:
   - The dataset was cleaned, merged, and formatted to ensure there were no missing values or duplicates. Outliers were handled, and relevant metrics such as daily steps, calories burned, and sleep were focused on.
   
2. **Exploratory Data Analysis (EDA)**:
   - Key statistics were calculated, such as the average number of steps taken per day, average sleep duration, and correlations between various health metrics like weight and steps.

3. **Visualizations**:
   - The following visualizations among others were created to help identify trends and relationships:
     - **Total Steps vs Calories Burned**: Shows a positive correlation between steps taken and calories burned.
     - **Activity Intensity vs Calories Burned**: Demonstrates that higher intensity activity results in higher calories burned.
     - **Total Time in Bed vs Total Minutes Asleep**: Highlights users’ sleep efficiency by comparing time in bed and actual sleep time.
     - **Weight vs Steps**: Shows the relationship between users’ weight and their daily step count.
     - **Steps vs Sleep Quality**: Examines how physical activity impacts sleep quality.

4. **Insights and Recommendations**:
   - Based on the data, the following insights were identified:
     - **Physical Activity**: Users averaged 7,418 steps per day, indicating room for improvement to reach the 10,000 steps/day goal.
     - **Sleep Efficiency**: Users typically spend more time in bed than actually sleeping, signaling an opportunity to promote sleep tracking features.
     - **Calories and Activity**: Users burn the most calories during periods of high-intensity activity, offering an opportunity for time-specific marketing campaigns.
   - **Recommendations**: 
     - Bellabeat should promote its activity trackers (Leaf and Time Watch) with fitness challenges.
     - Marketing should focus on sleep tracking features, emphasizing sleep efficiency.
     - Personalized weight and fitness plans should be promoted through Bellabeat Membership.

## **How to Run the Analysis**
1. **Prerequisites**:
   - Install the necessary R packages:
     ```R
     install.packages(c("tidyverse", "ggplot2", "lubridate", "dplyr", "tidyr"))
     ```

2. **Run the R Markdown File**:
   - Open the `bellabeat-casestudy.ipynb` file in Jupyter notebook.


3. **View the Final Report**:
   - Open the `Bellabeat Smart Device Data Analysis Report.pdf` to view the comprehensive analysis with visualizations and key insights.

## **Key Takeaways**
The Bellabeat case study showcases how data-driven insights can inform a company’s marketing strategy. By analyzing user behavior around physical activity, sleep, and calorie burn, Bellabeat can tailor its product offerings to better meet the needs of its users. This case study can also be used as part of your data analytics portfolio to demonstrate your ability to perform real-world business tasks and extract actionable insights from data.
