# Travel Data Analysis & Dashboard

## 📌 Project Overview

This project focuses on analyzing travel ticket data to identify patterns in ticket prices, travel routes, seat capacity, and occupancy rates.

The project covers the data preparation process, including data cleaning, preprocessing, feature engineering, exploratory data analysis, and data visualization using Python and Power BI.

The final results are presented through an interactive Power BI dashboard to provide a clearer view of travel and operational patterns.

## 🎯 Objectives

* Clean and prepare raw travel ticket data for analysis.
* Identify and handle missing values, duplicate records, and inconsistent data.
* Analyze ticket prices, routes, seat capacity, and occupancy.
* Create relevant features to support further analysis.
* Visualize the results through an interactive Power BI dashboard.
* Generate insights that can help understand travel and operational patterns.

## 🛠️ Tools & Technologies

* Python — Data cleaning, preprocessing, feature engineering, and analysis
* Google Colab — Data analysis environment
* Pandas — Data manipulation and preprocessing
* Power BI — Data visualization and dashboard development
* Microsoft Excel — Initial data inspection and validation

## 📊 Dataset

The dataset contains travel ticket information, including:

* Travel route
* Operator / transportation provider
* Seat class
* Seat type
* Ticket price
* Travel date
* Total seat capacity
* Occupied seats
* Remaining seats
* Occupancy rate
* Seat remaining rate

The final cleaned dataset contains **548,082 records** and **27 features**.

## 🧹 Data Cleaning & Preprocessing

Several data preparation steps were performed before the analysis:

* Checked and handled missing values.
* Checked duplicate records and duplicate IDs.
* Identified and handled invalid negative occupied-seat values.
* Removed ticket prices above 1,000,000 as outliers/inconsistent values for this analysis.
* Validated seat capacity and ticket price ranges.
* Created additional features to support the analysis.
* Calculated occupancy rate and seat remaining rate.

After the cleaning process:

* Rows: 548,082
* Features: 27
* Maximum seat capacity: 60
* Maximum ticket price: 630,369
  
## 🔍 Key Analysis

The analysis focuses on several aspects of the travel dataset:

### Route Analysis

The dataset contains several travel routes, with Bandung → Jakarta representing the largest share of records.

Other routes include:

* Bandung → Semarang
* Bandung → Surabaya
* Bandung → Yogyakarta
* Bandung → Serang

### Ticket Price

Ticket prices were analyzed across different routes, operators, and travel categories to identify differences in pricing patterns.

### Occupancy Analysis

Occupancy rate was calculated to measure how much of the available seat capacity was occupied.

For example:

> Occupancy Rate = Occupied Seats / Total Capacity × 100%

A higher occupancy rate indicates that a larger proportion of available seats were occupied.

### Seat Availability

The analysis also considers the remaining seat rate to understand seat availability across different travel segments.

## 📈 Power BI Dashboard

The cleaned and processed data was visualized using Power BI.

The dashboard consists of:

### Page 1 — Overview

Provides an overview of the dataset through key performance indicators and visualizations, including:

* Total trips
* Total ticket records
* Average ticket price
* Average occupancy rate
* Route distribution
* Price and occupancy patterns

### Page 2 — Key Insights

Highlights important findings from the analysis, including patterns in:

* Routes
* Ticket prices
* Occupancy
* Seat availability
* Transportation operators

## 🔄 Project Workflow

Raw Data
   ↓
Data Cleaning
   ↓
Data Preprocessing
   ↓
Feature Engineering
   ↓
Exploratory Data Analysis
   ↓
Power BI Visualization
   ↓
Dashboard & Insights

## 💡 Key Takeaways

This project demonstrates the process of transforming raw travel ticket data into a structured dataset and an interactive dashboard.

Through this project, I practiced:

* Data cleaning and validation
* Data preprocessing
* Feature engineering
* Exploratory data analysis
* Data visualization
* Dashboard development
* Communicating analytical findings

## 👩‍💻 Author

Neneng Nurhayasih

Fresh Graduate in Mathematics | Data Analytics & Statistics

Interested in Data Analysis, Data Visualization, and Statistics.
