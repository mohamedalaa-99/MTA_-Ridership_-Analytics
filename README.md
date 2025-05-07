MTA Ridership Analytics

📌 Project Overview

This repository contains the final project for MTA Ridership Analytics, including data preprocessing, analysis, and visualization using Power BI.

----------------------------------------------------------------------------------------------------------------------
🏆 Team Details
Team Name: Data Pioneers

Motto: "Data Pioneers – Transforming data into insights that drive success."

Selected Project: MTA Daily Ridership

Team Leader: Mohamed Alaa Mahmoud

👥 Team Members:

Mohamed Alaa Mahmoud Mohamed

Haneen Elsayed Mosbah Abdel Aziz

Ahmed Emadeldin Abdelmonim Elboghdady

Ganna Saad Khaled Elsaied El-Tabakh

Karim Mahmoud Mohamed Ibrahim

Hady Khaled Mohamed Ahmed


## Team Links
(Haneen) :  https://github.com/haneenmosbah/final-project

(Gana)   :  https://github.com/ganna123hesham/Depi-project

(Kareem) :  https://github.com/KarimMahmoud5124/Final-Project

(Ahmed)  :  https://github.com/Ahmed22741/final-project/tree/72bd7ba21fdab627a28cd14b9cdf740c52124c05

(Hady)   :  https://github.com/Hady7554/Final-project/tree/main
 -----------------------------------------------------------------------------------------------------------------------
📊 Step 1: Planning & Data Understanding

🔍 Understanding the Dataset

Key Columns:

Subways, Buses, LIRR, Metro-North, Access-A-Ride, Bridges and Tunnels, Staten Island Railway.

Total Estimated Ridership (absolute number of riders).

% of Comparable Pre-Pandemic Day (comparison to pre-pandemic levels).

Measures & Dimensions:

Measures (14 columns): Ridership & % of Pre-Pandemic Day for each transit mode.

Dimensions (2 columns): Date, Transit Mode.)

----------------------------------------------------------------------------------------------------------
🎯 Business Questions

Ridership Trends Over Time

How has total ridership in subways and buses changed before and after the pandemic?

Are there seasonal patterns in public transit usage?

What is the growth/decline rate of ridership over time?

What are the busiest months for ridership?

Rider Behavior and Usage Patterns

What are the top 5 busiest and least busy days in the subway?

Do public holidays affect ridership numbers?

What is the difference in ridership between weekdays and weekends?

Does an increase in car traffic reduce public transit ridership?

Post-Pandemic Recovery

Has public transit usage recovered to pre-pandemic levels?

How did the COVID-19 pandemic impact ridership?

Planning and Decision-Making Improvements

What are the peak hours when public transit demand is highest?

What is the average daily ridership in the subway?

What is the total number of passengers across all transportation modes per day?

Which mode of transportation has the highest ridership?

How can public transit services be improved based on ridership data? 

------------------------------------------------------------------------------------------------------------
📈 Main Metrics & KPIs

1️⃣ Public Transit Usage (Ridership Metrics)

✅ Total Ridership → Total number of passengers over a given period.

✅ Daily/Weekly/Monthly Ridership → Usage trends over time.

✅ Average Ridership per Station → Identifying busiest & least-used stations.

2️⃣ Transit Service Performance

✅ Total Trips per Day → Monitoring service frequency & consistency.

✅ Crowding Index → Measuring passenger load compared to capacity.

3️⃣ COVID-19 Impact & Recovery Trends

✅ Pre vs. Post-Pandemic Ridership → Recovery analysis.

✅ Monthly Ridership Growth (%) → Tracking ridership trends.

4️⃣ Seasonality & Passenger Behavior Trends

✅ Weekday vs. Weekend Ridership → Workdays vs. weekends analysis.

✅ Peak Hours Ridership (%) → Identifying busiest times of the day.

5️⃣ Service Optimization & Decision Making

✅ Top Busiest Stations → Recognizing high-demand locations. 

------------------------------------------------------------------------------------------------------
🎨 Dashboard Mockup - MTA Ridership Analysis

Color Palette

Primary Colors:

#E4EEF2 (Light Background)

#012E40 (Highlights & KPI Cards)

#AA5BF, #0ABF58, #012E40 (Charts & Graphs)

#0AA64D (Text & Contrast)

1️⃣ Strategic Dashboard - Performance & Efficiency Metrics

📉 Ridership Recovery vs. Pre-Pandemic

🕒 Service Performance & Delays

💡 Revenue & Ticketing Insights

2️⃣ Analytical Dashboard - Ridership & Trends Insights

📊 Overall Ridership Trends

📈 Mode-wise Ridership Analysis

🛑 Peak & Off-Peak Hours

3️⃣ Operational Dashboard - Real-Time Monitoring & Optimization

📡 Real-Time Ridership Tracking

🛠 Infrastructure Performance ✅ (Done)

🧹 Step 2: Data Cleaning & Preparation

Tools Used

Power BI (Power Query Editor)

3️⃣ Initial Data Assessment & Sources

Ridership data collected from multiple transit modes.

Contains columns for Date, Ridership Count, Transportation Mode, Pre/Post-Pandemic status.

4️⃣ Data Cleaning Steps

4.1 Unpivoting Data

Applied Unpivot Columns to convert transportation modes & values into a structured format.

Improved filtering & segmentation.

4.2 Removing Duplicates

Extracted a duplicate dataset & removed unnecessary columns.

Ensured unique values remain.

4.3 Creating Fact and Dimension Tables

Fact Table: Transactional ridership data.

Dimension Tables: Structured for better organization & analysis.

4.4 Creating Dimensional Tables

Dim Transportation Modes Table: Removed duplicates, linked to Fact Table.

Dim Calendar Table: Extracted Year, Month, Day, and Quarter from Date.

Linked both Dim Tables to Fact Table for improved analysis. 

5️⃣ Output & Deliverables

Cleaned Dataset → Ready for analysis.

Data Preprocessing Notebook → Documents all Power Query transformations.

------------------------------------------------------------------------------------------------------------------
🔗 Repository Structure

📂 MTA-Ridership-Analytics ├── 📂 Data │ ├── Raw_Dataset.csv │ ├── Cleaned_Dataset.csv │ 


├── 📂 Reports │ ├── Data_Preprocessing_Steps.pdf │ ├── Final_Presentation.pptx │


├── 📂 PowerBI_Dashboards │ ├── Strategic_Dashboard.pbix │ ├── Analytical_Dashboard.pbix │ ├── Operational_Dashboard.pbix │


├── README.md

🎯 Conclusion

This project provides a comprehensive analysis of MTA Ridership Trends using Power BI. The dashboards offer insights into public transit usage, post-pandemic recovery, and service optimization.

📌 Next Steps:

Enhance predictive analytics models.

Integrate real-time data feeds.

Improve visualization interactivity.

🚀 Stay tuned for future updates!
