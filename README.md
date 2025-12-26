City Hospital Emergency Room Patient Flow Analysis

Minor 1 – Exploratory Data Analysis (EDA)

📌 Project Description

This project focuses on analyzing patient flow in the Emergency Room (ER) of a city hospital using Exploratory Data Analysis (EDA) techniques.
The main aim is to study patient arrival patterns, identify peak hours, and understand how severity levels affect waiting time.

🎯 Objectives

Analyze patient arrival trends in the ER

Identify peak patient arrival hours

Study patient severity distribution

Analyze waiting time based on severity

Visualize ER congestion using line plots and heatmaps

📁 Dataset Information

The dataset used for this project is er_patient_flow.csv.

Columns Description
Column Name	Description
PatientID	Unique identifier for each patient
ArrivalDate	Date of patient arrival
ArrivalHour	Hour of arrival (24-hour format)
Gender	Gender of the patient
Age	Age of the patient
Severity	Emergency severity level (Low / Medium / High)
WaitingTime	Waiting time in minutes
🛠 Tools and Technologies Used

Python

Pandas – Data manipulation and analysis

Matplotlib – Data visualization

Seaborn – Advanced visualizations (heatmaps)

🔍 Methodology

Load and inspect the dataset

Handle missing values and format date columns

Group patients by arrival hour to identify peak times

Perform severity-wise waiting time analysis

Visualize trends using line plots, bar plots, and heatmaps

Interpret insights from visual results

📊 Visualizations Used

Line Plot – Patient arrival trend by hour

Heatmap – Patient arrivals by date and hour

Bar Plot – Average waiting time by severity level

🧠 Key Insights

Patient arrivals increase during evening hours

Peak congestion is observed between 6 PM and 10 PM

High severity patients experience the longest waiting times

ER workload increases as the day progresses

✅ Conclusion

The analysis reveals that emergency room congestion is highest during evening hours.
High-severity cases require more attention and result in longer waiting times.
These insights can help hospital management improve staff allocation and emergency response planning.

▶ How to Run the Project

Install required libraries:

pip install pandas matplotlib seaborn


Run the Python script:

python er_patient_flow_analysis.py

🚀 Future Scope

Include larger datasets for better accuracy

Analyze day-wise or weekly trends

Apply predictive analytics for patient arrival forecasting

👨‍🎓 Academic Use

This project is developed as part of Minor-1 EDA coursework and demonstrates practical application of data analysis and visualization techniques.
