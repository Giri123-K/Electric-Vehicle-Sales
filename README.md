Electric Vehicle Sales Analysis
Overview
This project analyzes electric vehicle (EV) sales data in India, providing insights into trends over time, state-wise distribution, and vehicle category preferences.

Dataset
The dataset contains records from 2014 to the present and includes the following columns:

Year: The year of the sales record

Month_Name: The month of the sales record

Date: The exact date of the sales record

State: The Indian state where the EV was sold

Vehicle_Class: Type of vehicle (e.g., Motor Car, Bus, Scooter)

Vehicle_Category: Category of the vehicle (e.g., 2-Wheelers, 4-Wheelers)

Vehicle_Type: Subtype classification (e.g., Personal, Shared)

EV_Sales_Quantity: The number of EVs sold

Data Processing
Loaded the dataset using pandas

Checked for duplicates and missing values (none were found)

Converted data types where necessary (e.g., Year to integer, Date to datetime)

Dropped unnecessary columns

Exploratory Data Analysis (EDA)
Yearly Trends: Analyzed EV sales growth over time

State-wise Analysis: Identified top states with the highest EV adoption

Vehicle Class & Category Insights: Found that two-wheelers dominate the market

Monthly Variations: Observed seasonal fluctuations in EV sales

Key Findings
EV sales have been increasing steadily

Maharashtra, Karnataka, and Uttar Pradesh lead in EV adoption

Two-wheelers are the most popular EV category

Public transport electrification (e.g., buses) remains limited but has growth potential

Tools & Libraries Used
Python (pandas, numpy, matplotlib, seaborn)

Jupyter Notebook

Next Steps
Analyze external factors (e.g., charging infrastructure, government incentives)

Predict future EV sales trends using machine learning

Compare India's EV market with global trends
