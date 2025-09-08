# 📊 Revenue and Customer Trends Dashboard (Excel Project)

This project showcases an end-to-end data analysis workflow entirely within Microsoft Excel. The goal was to transform raw transactional data into a fully interactive dashboard, moving from data cleaning and preparation to pivot tables and finally to dynamic visualizations that reveal key business insights. 

---

## 🛠️ What I Did: Key Tasks & Features
### Data Cleaning & Preparation
- Said goodbye to invalid entries like negative prices and quantities. 
- Added new columns for Day, Month, and Year to make date-based analysis.
- Calculated the profit for every single sale to see what was *really* driving the business.
- Built custom measures using DAX to unlock deeper, more powerful calculations beyond basic Excel formulas.
- Created a dedicated Calculations Sheet to cook up all the important metrics:
  - `Total Revenue = Price × Quantity`
  - Average Order Value (AOV)
  - Customer Purchase Frequency
  - Profit Margin Estimates
 

  - Recency, Frequency, and Monetary (RFM) Analysis
 
<img width="169" height="182" alt="image" src="https://github.com/user-attachments/assets/c557d925-6f17-4b92-ad5f-df848a620387" />

---

  - Price Elasticity for top-selling products.

<img width="737" height="597" alt="Screenshot 2025-09-08 152044" src="https://github.com/user-attachments/assets/94455a1f-accb-4d2d-9642-006ff808edf3" />

---
  - What-If Scenario Analysis to model how price changes could impact revenue.

<img width="1002" height="235" alt="Screenshot 2025-09-08 151926" src="https://github.com/user-attachments/assets/5fd87cf6-c99d-4979-896b-a037dfaa30d7" />

---

- A two-input data table to observe how varying price affects revenue generated yearly over time.

<img width="793" height="185" alt="Screenshot 2025-09-08 152002" src="https://github.com/user-attachments/assets/1b1802ce-797c-4929-b91e-aa0bf6743cfc" />



### Pivot Tables for Analysis
I created several pivot tables to summarise the data and explore different trends:
#### Revenue by Country  

<img width="175" height="446" alt="Screenshot 2025-09-08 134310" src="https://github.com/user-attachments/assets/ed78d8a5-20f4-4aa0-927d-380582ce476b" />

#### Countries with the highest sales 

<img width="273" height="150" alt="Screenshot 2025-09-08 134402" src="https://github.com/user-attachments/assets/fbfc15ff-7cb1-45e9-b254-391b13264308" />


#### Top Products by Revenue 📦

<img width="271" height="191" alt="Screenshot 2025-09-08 134352" src="https://github.com/user-attachments/assets/dc8d78ef-a2e2-4a83-94b6-f888b93ff526" />


#### Top Products that drive sales 

<img width="275" height="246" alt="Screenshot 2025-09-08 134425" src="https://github.com/user-attachments/assets/f23a72a4-da2a-42ab-bf53-cf0e7a269e73" />


### Top Customers by Revenue 🧑‍🤝‍🧑

<img width="267" height="151" alt="Screenshot 2025-09-08 134505" src="https://github.com/user-attachments/assets/14fa7ad4-8a6b-4521-8903-3c12767b0251" />


### KPI Cards
The Key performance indicators were created using pivot tables that were linked to the data model for an at-a-glance summary of the business health.
- ✅ Total Revenue  
- ✅ Total Products Sold
- ✅ Total Customers (Distinct Count)
- ✅ Average Revenue per Customer
- ✅ Top Customer



<img width="273" height="455" alt="Screenshot 2025-09-08 143140" src="https://github.com/user-attachments/assets/fdad0d28-5f89-4d47-aa18-971846d37a0e" />



### Interactive Dashboard
The final dashboard was built from the ground up with a focus on user experience and interactivity.
- Designed a clean layout using shapes and a custom colour palette.
##### Integrated dynamic filtering tools for such as:
  
- **Slicers** (Country, Product, Customer)  

<img width="337" height="137" alt="Screenshot 2025-09-08 142207" src="https://github.com/user-attachments/assets/4e230ada-9d3f-4b04-a4cc-710c30872f9d" />


  
- **Timeline** *(motnhs, years and quarters of the year)

<img width="319" height="131" alt="Screenshot 2025-09-08 142226" src="https://github.com/user-attachments/assets/f6f76fee-4ff8-45c8-ad1e-e33bf339d9e8" />



##### Included a variety of visualisations:
  - 📈 Line chart for revenue trends over time.
  - 📊 Bar charts for top products and customers.
  - 🌍 Map chart for a geographical view of revenue.
  - 🍩 Doughnut charts to show share-of-revenue.
  - 🟩 Tree map to visualise product category contributions.

---

## 📷 Dashboard Preview

**(Pro Tip: Replace the placeholder below with a screenshot of your finished dashboard!)**

<img width="1536" height="530" alt="Screenshot 2025-09-08 040723" src="https://github.com/user-attachments/assets/4ced35ae-a90c-4573-881a-698fd3ba80c5" />


---

<img width="1535" height="533" alt="Screenshot 2025-09-08 041132" src="https://github.com/user-attachments/assets/549d8ab2-f037-4d58-b6d6-201b4ae5f71a" />


---

<img width="1537" height="537" alt="Screenshot 2025-09-08 041218" src="https://github.com/user-attachments/assets/e26933b8-7807-4442-affd-f12ceeb9c9cd" />


---

<img width="1546" height="540" alt="Screenshot 2025-09-08 041415" src="https://github.com/user-attachments/assets/e3722df5-dd55-4639-ac99-eb03f9f569cc" />

---

<img width="1544" height="540" alt="Screenshot 2025-09-08 041545" src="https://github.com/user-attachments/assets/c3a8cb94-262d-40ee-9c4f-88d8a36bf4c9" />


---

<img width="1533" height="549" alt="Screenshot 2025-09-08 041626" src="https://github.com/user-attachments/assets/a94c67cf-1567-4e43-b5d0-49974076d0f9" />



## 💡 Key Insights Uncovered

- **Peak Performance:** September 2019 was the strongest month, driven by a spike in specific product sales.

<img width="1534" height="527" alt="Screenshot 2025-09-08 144241" src="https://github.com/user-attachments/assets/ac997bf8-7cb4-4483-abae-2cc505807a15" />


- **Top Products:** "Paper Craft Little Birdie", "Popcorn Holder" & "World War 2 Glider" emerged as the top revenue-driving products.
- **Customer Loyalty:**** The Pareto Principle was in full effect! A small handful of loyal customers drove a huge chunk of revenue. One customer (ID 1646) even went on a wild shopping spree for "Paper Craft Little Birdie" in September, spending over $80,000. Talk about a super-fan!
- **Business Growth:** Revenue in 2019 was significantly higher than in 2018, indicating steady business growth.

---

## 🏁 Final Thoughts

Phew! 😮‍💨😅 This project was a marathon, but I loved every minute. It pushed me to level up my skills in data storytelling, DAX, and dashboard design. I'm incredibly proud of how this turned from a mountain of messy data into something clean, interactive, and genuinely useful. 💪😌

My skills are constantly growing, and the best part is that I am having so much fun doing it. As I always say, onto the next project! 🚀

Thanks for checking this out! If you’re a recruiter, hiring manager, or fellow data nerd, I’d love to connect and hear your feedback.
