# Clustering Analysis for Airlines Data

## Objective
Perform clustering analysis (both **Hierarchical** and **K-Means clustering**) on the airline passenger data to determine the **optimum number of clusters**. The goal is to analyze and draw meaningful inferences from the obtained clusters.

---

## Dataset Overview
The dataset, **EastWestAirlines**, contains information on passengers enrolled in an airline's frequent flier program. It includes their mileage history and various ways they accrued or spent miles over the last year.

The aim is to identify **clusters of passengers with similar characteristics** to help the airline target different segments with personalized mileage offers.

---

## Data Dictionary

| Column                | Description                                                                      |
|----------------------|----------------------------------------------------------------------------------|
| **ID**                | Unique identifier for each passenger                                             |
| **Balance**           | Number of miles eligible for award travel                                       |
| **Qual_mile**         | Number of miles qualifying for Topflight status                                 |
| **cc1_miles**         | Miles earned with frequent flyer credit card in the past 12 months              |
| **cc2_miles**         | Miles earned with Rewards credit card in the past 12 months                     |
| **cc3_miles**         | Miles earned with Small Business credit card in the past 12 months              |
| **Bonus_miles**       | Miles earned from non-flight bonus transactions in the past 12 months            |
| **Bonus_trans**       | Number of non-flight bonus transactions in the past 12 months                    |
| **Flight_miles_12mo** | Number of flight miles in the past 12 months                                     |
| **Flight_trans_12**   | Number of flight transactions in the past 12 months                             |
| **Days_since_enrolled** | Number of days since enrollment in the frequent flier program                   |
| **Award**             | Indicates whether the passenger had an award flight (free flight) or not        |

### Credit Card Miles Categories:

- **1** = under 5,000 miles  
- **2** = 5,000 - 10,000 miles  
- **3** = 10,001 - 25,000 miles  
- **4** = 25,001 - 50,000 miles  
- **5** = over 50,000 miles  

---

## Analysis Plan
1. **Data Preprocessing:** Handle missing values, standardize data, and check for outliers.
2. **Hierarchical Clustering:** Use dendrograms to identify optimal clusters.
3. **K-Means Clustering:** Apply the elbow method to find the optimal number of clusters.
4. **Interpretation:** Analyze cluster characteristics and derive actionable insights.

---

## Expected Outcomes
- Identification of passenger segments with similar travel behaviors.
- Insights to help the airline develop targeted marketing strategies.

---

**Let's dive into the analysis and unlock meaningful patterns!**

