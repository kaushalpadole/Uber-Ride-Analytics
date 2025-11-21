# Uber-Ride-Analytics 🚕

This project analyzes Uber bookings, cancellations, ratings, and revenue using a combination of Excel for data cleaning & feature creation and Power BI for modeling, DAX, and dashboard visualization.
The dashboard highlights peak demand times, cancellation reasons, revenue distribution, and customer/driver behavior—all of which help in improving operational efficiency and ride experience.

# Business Problem ❔

Uber needs to solve challenges like:

1. High cancellation rates (both customer & driver)
2. Inconsistent supply during peak hours
3. Low driver ratings for certain vehicle types
4. Revenue fluctuations month-to-month
5. Customer dissatisfaction due to delays, wrong addresses, and vehicle issues

The aim is to extract actionable insights that improve customer satisfaction, ride completion, and revenue.

# Methodology 🪜 
## 1. Excel – Data Cleaning & Feature Engineering: 
Performed significant preprocessing in Excel, including:

- Removing duplicates & fixing inconsistent values
- Standardizing date/time formats
- Created Time of Day column (Morning, Afternoon, Evening, Night)
- Created Ride Distance column
- Ensured numeric/decimal values were modeled correctly

Excel prepared a clean and analysis-ready dataset.

## 2. Power BI – Data Modeling & DAX

- Imported cleaned Excel dataset
- Built star-schema relationships
- Created DAX measures for:
  Total Bookings
  Average CTAT & VTAT
  Customer & Driver Rating measures

## 3. Dashboard Development

Created an app-like, multi-page Power BI dashboard with:

Home - Cancellations - Ride Activity - Revenue - Ratings

Used slicers, navigation buttons, KPIs, trend charts, pied, donut charts, and card visuals.

# Skills Used 🤹

1. Excel Skills
2. Data Cleaning
3. Creating derived columns (Time of Day, Ride Distance)
4. Cleaning text, numeric & categorical fields
5. Power BI Skills
7. DAX Measures
8. Analytics Skills
9. Cancellation Root Cause Analysis
10. Revenue Interpretation
11. Customer & Driver Behavior Study
12. Insight Storytelling

# Results 🔍 
## 1. Ride Demand 📈
   Morning has the highest bookings (45K)
   Autos & Go Mini are the most frequently booked vehicles
   
## 2. Cancellations ❌
   Total incomplete rides: 9K
   Top customer reasons:
   - Wrong address
   - Change of plans
   - Driver not moving
   Top driver reasons:
   - Customer misconduct
   - More passengers than allowed
   - Personal/vehicle issues

## 3. Revenue 💰
- Auto generates the highest revenue at ₹12.9M
- Go Mini, Go Sedan follow next
- UPI (45%) is the most used payment method

## 4. Ratings 5️⃣
   Customer ratings highest for: Uber XL & Premier Sedan
   Driver ratings lowest for: Auto & Go Sedan (needs improvement)

## 5. Ride Distance Pattern 🧩
   Ride distances grouped into 1–10, 11–20, 21–30 km groups show consistent booking volume
   Longer rides (>40 km) have lower volume but higher value

# Business Recommendations 💡

## 1. Reduce Cancellations
- Allow customers to easily change pickup location
- Improve driver movement tracking in-app
- Introduce cancellation penalties only after proper investigation

## 2. Fleet Optimization
- Increase Auto/Go Mini supply during mornings
- Improve XL & Premier Sedan availability on weekends/evenings

## 3. Improve Driver Ratings
- Targeted training for Auto & Go Sedan drivers
- Improve navigation & customer interaction guidelines

## 4. Revenue Growth
- Offer deals during slow months (Feb, Sept)
- Promote UPI/wallet payments with cashback

## 5. Customer Satisfaction
- Quick resolution for vehicle breakdown & AC complaints
- Reward high-value customers

# Dashboard:
Home:
<img width="1516" height="770" alt="Home" src="https://github.com/user-attachments/assets/edf09e89-d402-4405-8679-0e3d7751ed1c" />
Cancellations: 
<img width="1489" height="761" alt="Cancellations" src="https://github.com/user-attachments/assets/1263fdfc-b522-4cb7-a6dd-fe1a1f3f955b" />
Ride Activity:
<img width="1493" height="766" alt="Ride Activity" src="https://github.com/user-attachments/assets/a1d3ad9e-365b-4fa9-a91e-17f4400a8907" />
Revenue:
<img width="1422" height="765" alt="Revenue" src="https://github.com/user-attachments/assets/4e28cd8f-17fe-4cf6-9304-a6b1c9cfc010" />
Ratings:
<img width="1441" height="772" alt="Ratings" src="https://github.com/user-attachments/assets/6c796801-ffef-4ce0-b122-2b8ecea3edd1" />


