# Student Digital Wellness & Behavioral Data Analysis

📌 Project Overview
This project performs an in-depth Exploratory Data Analysis (EDA) on the social media habits of students to understand the relationship between digital engagement, mental health, and academic performance. By analyzing over 700 student records, this study identifies critical thresholds where social media usage begins to negatively impact physical and psychological well-being.

📊 Key Findings & Insights
Mental Health Correlation: Discovered a near-perfect inverse correlation of -0.95 between social media addiction scores and mental health stability.

The Sleep-Usage Trade-off: Identified a -0.76 correlation between daily usage and sleep hours, with a sharp decline in rest after exceeding 4 hours of daily screen time.

Academic Impact: Approximately 64.1% of students surveyed acknowledged that social media has a direct negative impact on their academic performance.

Social Conflict: A strong positive correlation of 0.83 was found between addiction levels and the frequency of social conflicts.

🛠️ Tech Stack
Language: Python

Libraries: * Pandas: Data manipulation and cleaning.

Seaborn & Matplotlib: Advanced statistical data visualization.

NumPy: Numerical processing.

📈 Visualizations Included
Correlation Heatmaps: Mapping the interconnectedness of usage, sleep, and mental health.

Violin & Boxen Plots: Analyzing the distribution of addiction across different academic levels.

Joint & KDE Plots: Visualizing the probability density of usage hours vs. sleep deprivation.

Donut Charts: Categorical breakdown of academic performance impacts.

Bubble Charts: Multi-dimensional analysis of Age, Usage, and Addiction severity.

📂 Dataset
The dataset contains 705 entries with the following key features:

Age, Gender, Academic_Level

Most_Used_Platform

Avg_Daily_Usage_Hours

Sleep_Hours_Per_Night

Addicted_Score (Calculated Metric)

Mental_Health_Score

🚀 How to Run
Clone this repository.

Ensure you have Python installed along with the required libraries:

Bash
pip install pandas seaborn matplotlib numpy
Open the Jupyter Notebook:

Bash
jupyter notebook "Student Digital Wellness & Behavioral Data Analysis.ipynb"
Run all cells to reproduce the analysis and visualizations.

🎓 Conclusion
The analysis concludes that social media addiction is a significant predictor of diminished mental health and sleep quality in students. The data suggests that keeping daily usage below a 4-hour threshold is essential for maintaining optimal academic and psychological wellness.