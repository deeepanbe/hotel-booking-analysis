# 📊 Hotel Booking Analysis Report

This project explores and analyzes hotel booking data to uncover insights about booking patterns, cancellation behavior, market segment trends, and average daily rates (ADR) across time. The analysis was done using Python, pandas, and visualization libraries like Matplotlib and Seaborn.

---

## 🗂️ Dataset Overview

- Dataset: `hotel_bookings.csv`
- Records: ~119,000
- Features include: `hotel type`, `country`, `market segment`, `is_canceled`, `adr`, `arrival_date`, and more.

---

## 🧹 Data Cleaning

- Standardized column names to lowercase
- Converted date fields and derived additional fields like `month` and `quarter`
- Handled missing values appropriately

---

## 📈 Key Analyses & Visualizations

### 1. 🔄 Cancellations by Hotel Type
- City Hotel had higher cancellation rates compared to Resort Hotel
- Pie chart and bar plots used to visualize cancellation ratios

### 2. 🌍 Top 10 Countries by Cancellations
- Most cancellations came from Portugal, the UK, France, and others
- Visualized using a pie chart

### 3. 🏷️ Market Segment Analysis
- **Online TA (Travel Agents)** is the most dominant market segment
- Direct bookings showed fewer cancellations
- Pie chart and bar plot used to compare segment performance

### 4. 💰 ADR (Average Daily Rate) by Month & Hotel Type
- City Hotel had peak ADR in summer months (July–August)
- Resort Hotel showed more balanced ADR throughout the year
- Bar chart grouped by hotel type and month

### 5. 🕓 Quarterly ADR Trends
- Q3 showed the highest ADR across both hotel types
- Useful for revenue management and pricing decisions
- Line plot used to show quarterly trend

---

## 🧠 Business Insights

- High cancellations from specific countries → Target these markets with flexible policies
- Q3 is revenue peak → Adjust staffing, inventory, and marketing accordingly
- Focus on **Direct** and **Corporate** segments to reduce cancellations
- Invest in improving **Online TA** booking experience

---

## 📎 Technologies Used

- Python (Pandas, Matplotlib, Seaborn)
- Jupyter Notebook
- Exported as PDF for documentation

---

## 📤 How to Run

```bash
# Clone the repo
git clone https://github.com/yourusername/hotel-booking-analysis.git

# Navigate and open the notebook
cd hotel-booking-analysis
jupyter notebook hotelbooking.ipynb
