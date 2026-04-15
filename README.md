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

Libraries: * `Pandas`: Data manipulation and cleaning.

`Seaborn & Matplotlib`: Advanced statistical data visualization.

`NumPy`: Numerical processing.

📈 Visualizations Included

**Correlation Heatmaps**: Mapping the interconnectedness of usage, sleep, and mental health.
<img width="1000" height="600" alt="image" src="https://github.com/user-attachments/assets/c8e0b8db-088d-4f57-8e68-ffe398f4212c" />

**Violin & Boxen Plots**: Analyzing the distribution of addiction across different academic levels.
<img width="1000" height="600" alt="image" src="https://github.com/user-attachments/assets/8036b7a8-48b3-48ee-b5cf-eb17659a686b" />

**Joint & KDE Plots**: Visualizing the probability density of usage hours vs. sleep deprivation.
<img width="1000" height="600" alt="image" src="https://github.com/user-attachments/assets/2c014177-0678-4d23-b5a7-a9250db30a35" />


**Donut Charts**: Categorical breakdown of academic performance impacts.
<img width="706" height="539" alt="image" src="https://github.com/user-attachments/assets/445703d8-b675-44bc-bf71-f9302a35db0a" />


📂 Dataset
The dataset contains 705 entries with the following key features:

`Age`, `Gender`, `Academic_Level`

`Most_Used_Platform`

`Avg_Daily_Usage_Hours`

`Sleep_Hours_Per_Night`

`Addicted_Score` (Calculated Metric)

`Mental_Health_Score`

🚀 How to Run
Clone this repository.

Ensure you have Python installed along with the required libraries:

`Bash`

`pip install pandas seaborn matplotlib numpy`
Open the Jupyter Notebook:

`Bash`

`jupyter notebook` "Student_Digital_Wellness_Analysis.ipynb"
Run all cells to reproduce the analysis and visualizations.

## 🛠️ Tech Stack
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-%234479A1.svg?style=for-the-badge&logo=Seaborn&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)

🎓 Conclusion
The analysis concludes that social media addiction is a significant predictor of diminished mental health and sleep quality in students. The data suggests that keeping daily usage below a 4-hour threshold is essential for maintaining optimal academic and psychological wellness.
