# Hotel Booking Customer Retention and Dynamic Pricing Analysis

## Project Overview

This project analyzes hotel booking data to identify customer booking behavior, cancellation patterns, and factors affecting hotel revenue. The objective is to generate actionable business insights that can improve customer retention and support dynamic pricing strategies.

## Dataset Size Overview

The analysis is performed on 84,889 hotel booking records from City Hotels and Resort Hotels.

## Business Problem

Hotels experience significant revenue loss due to booking cancellations and ineffective pricing strategies. This project aims to:

* Identify key factors influencing booking cancellations.
* Analyze customer booking behavior.
* Explore pricing patterns using ADR (Average Daily Rate).
* Support data-driven decision-making for customer retention and revenue optimization.

## Dataset Information

* Dataset: Hotel Booking Demand Dataset
* Total Records: 84,889+
* Hotel Types: City Hotel and Resort Hotel
* Features: Booking details, customer information, stay duration, pricing, cancellations, and special requests.

## Tools and Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* SQL
* Power BI
* Git & GitHub
* Jupyter Notebook

---

# Project Workflow

## Week 1: Data Cleaning and Feature Engineering

### Data Cleaning

* Handled missing values and data quality issues.
* Removed duplicate records.
* Treated outliers using statistical techniques.
* Prepared a clean dataset for analysis and modeling.

### Feature Engineering

Created business-focused features to enhance analysis:

* Total Stay Nights
* Total Guests
* Total Revenue

---

## Week 2: Exploratory Data Analysis (EDA)

### Analysis Performed

* Hotel Type Distribution
* Cancellation Analysis
* Monthly Booking Trends
* Lead Time Analysis
* ADR (Average Daily Rate) Analysis
* Market Segment Analysis
* Correlation Analysis

### Key Findings

* City Hotels received more bookings than Resort Hotels.
* Customers who cancelled bookings had significantly higher lead times than those who completed their stay.
* Cancelled bookings had a higher average ADR (106.33) compared to non-cancelled bookings (70.39).
* Online Travel Agency bookings represented the largest booking segment.
* Special requests and parking requirements showed negative correlation with cancellations.

---

## Week 3: Power BI Dashboard Development

Developed an interactive Power BI dashboard to analyze hotel performance, customer behavior, and revenue trends.

### Dashboard Features

* 5 KPI Cards for key performance metrics.
* Monthly booking trend analysis.
* Hotel type comparison (City Hotel vs Resort Hotel).
* Cancellation analysis.
* ADR and revenue analysis.
* Interactive slicers for dynamic filtering.

## Dashboard Preview

![Hotel Booking Dashboard](Images/Hotel_Booking_Dashboard.png)

---

## Week 4: Dashboard Enhancement

Improved dashboard usability and business presentation by implementing:

* Implemented a Month Dimension table to enable accurate chronological sorting.
* Added Business Insights section for management-level interpretation.
* Improved dashboard layout and visualization clarity.

---

## Business Insights

* Peak bookings are observed during July and August.
* City Hotels experience higher cancellation rates compared to Resort Hotels.
* ADR increases during high-demand periods.
* Longer lead times indicate higher cancellation risk.
* Dynamic pricing strategies can help improve revenue optimization.

---

## Repository Structure

```text
Hotel-Booking-Customer-Retention-Analysis/

├── Data/
│   ├── hotel_bookings.csv
│   └── hotel_bookings_cleaned.csv

├── notebooks/
│   ├── 1-Data_Cleaning.ipynb
│   └── 2_EDA_and_Statistical_Testing.ipynb

├── PowerBI/
│   └── Hotel_Booking_Dashboard.pbix

├── images/
│   └── hotel_booking_dashboard.png

└── README.md
```

---

## Current Status

✅ Data Cleaning Completed  
✅ Feature Engineering Completed  
✅ Exploratory Data Analysis Completed  
✅ Statistical Analysis Completed  
✅ Power BI Dashboard Completed  
✅ Business Insights Added  

---

## Future Enhancements

* Customer segmentation analysis.
* Booking demand forecasting.
* Revenue prediction model.
* Automated KPI reporting.

