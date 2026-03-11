# ✈️ Airline Passenger Satisfaction Analysis (Tableau)

A data analytics project that analyzes airline passenger satisfaction using Tableau dashboards to identify the key drivers of customer experience and operational performance.

## 📌 Project Overview

This project analyzes airline passenger satisfaction using Tableau to understand the key factors affecting customer experience.

The analysis focuses on two major aspects:

• Operational performance (flight delays)
• Service quality (seat comfort, entertainment, food, cleanliness, WiFi)

The project includes data preprocessing, exploratory analysis, dashboard development, and business insight generation to help airline management improve passenger satisfaction.

## ❓ Key Business Questions

The analysis was performed to answer the following business questions:

1. What is the overall passenger satisfaction rate?
2. How does satisfaction vary across passenger classes?
3. Does travel type (Business vs Personal) influence satisfaction?
4. How does customer loyalty affect satisfaction?
5. What is the relationship between flight delays and passenger satisfaction?
6. At what delay threshold does satisfaction significantly decrease?
7. Which service attributes have the strongest impact on satisfaction?
8. Which passenger segment produces the highest satisfaction probability?
9. Does service quality or operational delay have a greater impact on satisfaction?

## 📊 Dataset

The dataset contains airline passenger feedback and service ratings collected from customer surveys.

### Key variables include

• Passenger Class
• Travel Type
• Customer Type
• Flight Distance
• Arrival Delay
• Departure Delay
• Passenger Satisfaction

### Service Rating Features

• Seat Comfort
• Food and Drink
• Inflight Entertainment
• Inflight WiFi
• Cleanliness
• On-board Service


## 📊 Dataset

The dataset contains airline passenger feedback and service ratings collected from customer surveys.

### Key variables include

• Passenger Class
• Travel Type
• Customer Type
• Flight Distance
• Arrival Delay
• Departure Delay
• Passenger Satisfaction

### Service Rating Features

• Seat Comfort
• Food and Drink
• Inflight Entertainment
• Inflight WiFi
• Cleanliness
• On-board Service


## ⚙️ Data Preprocessing

Several preprocessing steps were performed before analysis:

• Verified and corrected data types
• Checked and handled missing values
• Created calculated fields required for analysis
• Prepared metrics for satisfaction probability analysis

### Calculated Fields

**Total Delay**

Total Delay = Arrival Delay + Departure Delay

**Satisfaction Probability**

IF [Satisfaction] = "satisfied" THEN 1 ELSE 0 END

This calculated field allows satisfaction to be analyzed as a probability using average values.


## ⚙️ Data Preprocessing

Several preprocessing steps were performed before analysis:

• Verified and corrected data types
• Checked and handled missing values
• Created calculated fields required for analysis
• Prepared metrics for satisfaction probability analysis

### Calculated Fields

**Total Delay**

Total Delay = Arrival Delay + Departure Delay

**Satisfaction Probability**

IF [Satisfaction] = "satisfied" THEN 1 ELSE 0 END

This calculated field allows satisfaction to be analyzed as a probability using average values.


## 📈 Dashboard Overview

An interactive Tableau dashboard was built to visualize key business insights.

### Dashboard Components

• Overall Satisfaction KPI
• Average Total Delay
• Average Service Quality Score
• Class-wise Satisfaction Analysis
• Travel Type Satisfaction Comparison
• Customer Loyalty Satisfaction Analysis
• Delay Impact Comparison
• Service Quality Heatmap
• Passenger Segment Ranking

## 🖥️ Dashboard Preview

### Executive Dashboard
### Delay Impact Analysis
### Service Quality Heatmap


## 🔍 Key Insights

### Overall Satisfaction

The overall passenger satisfaction rate is **43.9%**, indicating significant room for improvement in airline services.

### Passenger Class Impact

Business class passengers have the highest satisfaction rate (**69.5%**) compared to economy passengers.

### Travel Type Impact

Passengers traveling for business purposes report higher satisfaction compared to personal travel passengers.

### Delay Impact

Severe flight delays greater than **60 minutes significantly reduce passenger satisfaction**.

### Service Quality Drivers

Seat comfort, inflight entertainment, and cleanliness are the most influential service attributes affecting satisfaction.


## 📌 Strategic Recommendations

Based on the analysis, the following strategies are recommended:

1. **Reduce Operational Delays**
   Improve scheduling efficiency and airport operations to minimize severe delays.

2. **Enhance Key Service Attributes**
   Improve seat comfort, inflight entertainment, and cabin cleanliness to increase passenger satisfaction.

3. **Focus on High-Value Passenger Segments**
   Provide loyalty programs and personalized services for business travelers and frequent flyers.


## 🛠️ Tools and Technologies Used

• Tableau
• Data Visualization
• Business Analytics
• Data Analysis


## 👤 Author

Beduduri Yaswanth Reddy

Aspiring Data Analyst | Data Visualization Enthusiast

If you found this project useful:

⭐ Star the repository

📩 Connect with me on LinkedIn:  
https://www.linkedin.com/in/beduduri-yaswanth-reddy-data-analyst-ai?lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_view_base_contact_details%3BRlTjMwDKRhqo%2Br%2Bin1buTg%3D%3D

