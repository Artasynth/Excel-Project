# **Los Angeles Crime Data Analysis (2023-2024)**  

## **Overview**  
Imagine receiving a **large and untidy dataset**, tasked with extracting **meaningful insights** from it. At first glance, the dataset may seem overwhelming—**missing values, inconsistent formats, and messy layouts** obscure the valuable information buried within. This is a challenge many analysts face: transforming chaos into **actionable insights** using the tools at their disposal.  

For this portfolio project, I relied solely on **Microsoft Excel**. While Excel has limitations in handling massive datasets or advanced machine learning, its **versatility and accessibility** make it a powerful tool for a wide range of **data analysis workflows**. From **data cleaning and transformation** to **statistical analysis and visualization**, Excel enables meaningful insights even from the most unstructured datasets.  

## **Data Preparation & Analysis**  
The analysis began with a **comprehensive data-cleaning process**:  
- ✅ **Correcting errors** and handling missing values to ensure data integrity  
- ✅ **Reshaping the dataset** to capture richer details while removing redundancies  
- ✅ **Leveraging Excel’s analytical tools**—Dynamic Arrays, Pivot Tables, Analysis ToolPak, and Charts—to extract insights  

As patterns and trends began to emerge, I explored **crime distributions, seasonal fluctuations, and demographic influences** to identify meaningful takeaways.  

## **Example Questions and Potential Insights**  
During the analysis, I explored several key questions to uncover crime patterns and trends in Los Angeles:  

- 📌 **What are the crime trends over time?**  
- 📌 **What times of the day are most prone to criminal activity?**  
- 📌 **Is there a seasonal or monthly variation in crime rates?**  
- 📌 **How has the rate of specific crimes changed over time?**  
- 📌 **Which neighborhoods or areas have the highest crime rates?**  
- 📌 **How does crime differ across neighborhoods?**  
- 📌 **What are the most common types of crimes in Los Angeles?**  
- 📌 **Are there patterns in victim demographics?**  
- 📌 **Is there a correlation between the ethnicity of victims and specific crime types?**  
- 📌 **And more...**  

## **The Story Behind the Data**  
Understanding crime patterns is **crucial for prevention**. By analyzing crime data, we can identify **trends, influencing factors, and correlations** that empower decision-makers and the public to implement **data-driven crime reduction strategies**.  

The period from **2020 to 2024** was marked by **global and national events** that had profound effects on society. From the **COVID-19 pandemic** to **economic shifts, protests, inflation, and geopolitical conflicts**, such events have ripple effects that influence many aspects of life—including crime rates.  

### **Key Societal Events (2020-2024)**  
- 📌 **2020**: COVID-19 pandemic, George Floyd protests, 2020 U.S. Presidential Election, California wildfires  
- 📌 **2021**: Biden’s inauguration, Afghanistan troop withdrawal, tech industry turbulence, rising inflation  
- 📌 **2022**: Russia-Ukraine war, highest U.S. inflation since 1981, continued social unrest, legislative changes  
- 📌 **2023**: Bank failures, debt ceiling crisis, extreme weather events, post-pandemic economic recovery  
- 📌 **2024**: Middle East conflicts, U.S. presidential election, record-breaking global temperatures  

At first glance, these events may seem unrelated to crime rates. However, **data suggests otherwise**—macro-level factors like **economic downturns, inflation, and public unrest** often correlate with shifts in crime patterns. To explore this **interplay between societal changes and crime trends**, I analyzed a **publicly available crime dataset for Los Angeles (2020-present)**.  

## **Dataset Description**  
The **Los Angeles Crime Dataset** ([Crime Data from 2020 to Present](#)) contains records of crime incidents in Los Angeles from 2020 onward, transcribed from original crime reports by the LAPD. To ensure privacy, address fields are anonymized to the nearest hundred block. The dataset comprises **over a million rows** and includes **28 columns of information**.  

### **Variable Dictionary**  

| Variable        | Data Type  | Description |
|----------------|-----------|-------------|
| **DR_NO**      | Text      | Division of Records Number: Official file number (Year, Area ID, and 5 digits) |
| **Date Rptd**  | Timestamp | Reporting Date (MM/DD/YYYY) |
| **DATE OCC**   | Timestamp | Crime Occurrence Date (MM/DD/YYYY) |
| **TIME OCC**   | Text      | Crime Occurrence Time (24-hour format) |
| **AREA**       | Text      | 21 Community Police Stations numbered 1-21 |
| **AREA NAME**  | Text      | Names of Community Police Stations |
| **Rpt Dist No**| Text      | 4-digit code of sub-area |
| **Crm Cd**     | Text      | Crime code |
| **Crm Cd Desc**| Text      | Crime code Description |
| **Mocodes**    | Text      | Modus Operandi: Activities associated with the suspect |
| **Vict Age**   | Text      | Victim Age |
| **Vict Sex**   | Text      | Victim sex (F – Female, M – Male, X – Unknown) |
| **Vict Descent** | Text    | Victim ethnicity (A - Other Asian, B – Black, C – Chinese, D – Cambodian, etc.) |
| **Premis Cd**  | Number    | Type of structure, vehicle, or location where the crime took place |
| **Premis Desc**| Text      | Description of premise type |
| **Weapon Used Cd** | Text  | Code for the type of weapon used |
| **Weapon Desc** | Text     | Description of weapon code used |
| **Status**     | Text      | Status of the case (IC is the default) |
| **Status Desc**| Text      | Description of status code used |
| **Crm Cd 1**   | Text      | Primary and most serious crime committed |
| **Crm Cd 2**   | Text      | Secondary crime code, less serious than Crime Code 1 |
| **Crm Cd 3**   | Text      | Third crime code, less serious than Crime Code 2 |
| **LOCATION**   | Text      | Street address rounded to the nearest hundred block |
| **Cross Street** | Text    | Cross Street of the rounded Address |
| **LAT**        | Number    | Latitude |
| **LON**        | Number    | Longitude |

## **Why This Matters**  
This project highlights the importance of **data-driven decision-making** in public policy and safety. By analyzing real-world crime data, we can uncover:  
- 🔍 **Trends in crime rates over time**  
- 🔍 **The impact of societal and economic shifts on criminal activity**  
- 🔍 **Patterns in crime distribution by location, time, and demographics**  

## **Final Thoughts**  
This project demonstrates how **Excel remains a powerful tool** for analyzing real-world datasets. Through careful **data cleaning, visualization, and analysis**, Excel enables us to extract **meaningful insights** and tell compelling stories hidden within raw data.  
