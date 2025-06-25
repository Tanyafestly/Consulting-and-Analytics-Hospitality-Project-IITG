# 🏨 Optimizing Revenue Leakage & Profitability in the Hospitality Sector

This is a business intelligence project built using Power BI that analyzes a large-scale hotel booking dataset to identify revenue leakage, cancellation trends, platform inefficiencies, and underutilized room capacity. The goal is to propose **data-backed strategies** that improve profitability and guest conversion in the hospitality industry.

---

## 🎯 Objective

To analyze 135,000+ hotel bookings across cities, room categories, and booking platforms, and identify:
- Patterns in booking behavior
- Revenue leakage from cancellations
- Occupancy gaps and low-performing hotels
- Room preference trends

Using these insights, the project proposes 5 key recommendations backed by business metrics and scenario-based financial impact modeling.

---

## 🛠 Tools Used

| Tool     | Purpose                                      |
|----------|----------------------------------------------|
| **Power BI** | Data modeling, DAX measures, dashboards |
| **Excel**    | Initial data exploration & cleaning      |
| **DAX**      | KPI calculation and measure logic         |
| **GitHub**   | Project hosting & version tracking        |

---

## 📦 Dataset Structure

The data comprises 135,000+ rows across these key tables:

- `fact_bookings`: Raw booking data with status, revenue, platform, etc.
- `fact_aggregated_bookings`: Summarized booking records
- `dim_date`: Day, weekday/weekend, and time context
- `dim_hotels`: Hotel details like name, location, city
- `dim_rooms`: Room ID, class (Standard, Premium, Elite, Presidential)

---

## 📊 Key KPIs Created

| KPI                        | What It Tells Us                              |
|-----------------------------|-----------------------------------------------|
| **Total Revenue**         | Overall revenue realized                      |
| **Rooms Sold**            | Number of successfully completed bookings     |
| **Occupancy Rate**        | Utilization of available room capacity        |
| **ADR (Avg Daily Rate)**  | Revenue per occupied room                     |
| **RevPAR**                | Revenue per available room                    |
| **Cancellation Rate**     | % of bookings that were canceled              |
| **Revenue Lost**          | Value of bookings lost due to cancellation    |
| **Booking Conversion Rate** | % of bookings completed                     |
| **Avg Length of Stay**    | Nights per successful booking                 |

---

## 📈 Dashboard & Visuals

Each recommendation in this project is supported by **Power BI visuals**:

| Slide / Visual                            | Key Takeaway                                           |
|-------------------------------------------|--------------------------------------------------------|
| KPI Cards                                 | Overview of revenue, occupancy, and ADR               |
| Cancellation Rate + Revenue Lost Chart    | Identifies cancellation as biggest leak               |
| Revenue by Booking Platform (Bar Chart)   | Reveals OTA dependency and cancellation risk          |
| Revenue Over Time (Line Chart)            | Seasonal patterns and trend identification            |
| Room Class Preference (Donut Chart)       | Highlights room type demand distribution              |
| Weekend vs Weekday Booking (Stacked Chart)| Shows upsell opportunity for premium rooms            |
| Revenue by City & Hotel (Treemaps)        | Detects underperforming locations and properties      |

---

## 💡 Strategic Recommendations

1. **Reduce Cancellations**  
   Stricter policies + prepayment incentives to curb 24.83% cancellation rate.

2. **Improve Occupancy**  
   Run city-specific campaigns, offer midweek corporate bundles, and targeted ads.

3. **Optimize Platform Mix**  
   Shift focus to direct bookings and renegotiate high-commission OTA deals.

4. **Dynamic Pricing by Day Type**  
   Apply day-wise pricing to maximize weekend revenue and boost midweek occupancy.

5. **Upsell and Reposition Luxury Rooms**  
   Bundle underperforming Presidential rooms with perks; offer limited-time upgrades.

---

## 💰 ROI & Payback Analysis

| Component                              | Value                          |
|----------------------------------------|--------------------------------|
| Estimated Annual Revenue Gain          | ₹240M – ₹270M                  |
| One-Time Implementation Cost           | ₹1.2M                          |
| **ROI**                                | 199x – 224x                    |
| **Payback Time**                       | 1.5 to 2 weeks                 |

---

### 💸 Revenue Gain Breakdown

| Area of Impact                  | Estimated Gain (₹) |
|----------------------------------|--------------------|
| Reduced Cancellations            | ₹50M               |
| Improved Occupancy (5%)          | ₹85M – ₹120M       |
| Platform Optimization            | ₹30M               |
| Room Upselling & Bundling        | ₹15M – ₹20M        |
| Dynamic Pricing Adjustments      | ₹25M – ₹30M        |
| **Total Gain**                   | **₹240M – ₹270M**  |

---

### 🔮 Scenario Analysis

- **🚀 Best Case**  
  10% fewer cancellations, 8% more occupancy, major shift to direct bookings  
  → **₹400M+ gain**

- **✅ Most Likely Case**  
  5% fewer cancellations, 5% occupancy boost, moderate success in upselling  
  → **₹240M – ₹270M gain**

- **📉 Worst Case**  
  2% cancellation drop, minor traction in pricing/shift  
  → **₹50M – ₹80M gain**

---

## 📂 Files in This Repository

| File                                   | Description                               |
|----------------------------------------|-------------------------------------------|
| [PowerBI_Dashboard.pbix](https://github.com/Tanyafestly/Consulting-and-Analytics-Hospitality-Project-IITG/blob/main/IITG_The_Diva_project_final.pbix)              | Power BI dashboard with all visuals & DAX |
| [Presentation_Deck.pdf](./Presentation_Deck.pdf)               | Final report presentation (recommendations + insights) |
| [README.md](./README.md)                           | This project summary                      |
| [fact_bookings.csv](./Raw_Data/fact_bookings.csv) | Raw booking data                          |
| [dim_hotels.csv](./Raw_Data/dim_hotels.csv)       | Hotel master data                         |
| [dim_rooms.csv](./Raw_Data/dim_rooms.csv)         | Room master data                          |
| [Screenshots](https://github.com/Tanyafestly/Consulting-and-Analytics-Hospitality-Project-IITG/blob/main/Dashboard.pdf.pdf)                    | Visuals used for insight justification    |

---

## ✨ Author

**Tanya Singh**  
B.A. Business Economics | Data Analytics & Strategy Enthusiast  
[GitHub Profile](#) • [LinkedIn](#) • [Email](#)

---

## 📌 Want to Use This Project?

1. Clone or download this repository  
2. Open `PowerBI_Dashboard.pbix` in Power BI Desktop  
3. Explore visual filters and drill-downs  
4. Check the slide deck for business recommendations  
5. Feel free to adapt for hotel, travel, or service-based analytics problems

---

