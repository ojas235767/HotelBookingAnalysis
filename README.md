# 🏨 Hotel Booking Analysis

This project explores over 1.19 lakh hotel booking records to uncover patterns in customer behavior, cancellation trends, and seasonality. Using Python, Excel, and Power BI, it delivers actionable insights and strategic recommendations to improve hotel retention and revenue.

## 🎯 Objective
To analyze large-scale hotel booking data to:
- Identify key drivers of booking cancellations
- Understand guest behavior and seasonality
- Propose data-driven strategies to reduce cancellations and boost customer satisfaction

## 📂 Dataset
- Records: 1,19,000+ booking entries  
- Source: [Hotel Booking Demand Dataset](https://www.kaggle.com/datasets/jessemostipak/hotel-booking-demand)  
- Features include:
  - Booking dates, hotel type, lead time  
  - Guest count, cancellation status  
  - Country, ADR (average daily rate), special requests  
  - Meal type, market segment, etc.

## 🛠 Tools & Technologies
- Python: `Pandas`, `NumPy`, `Matplotlib`, `Seaborn`
- Excel: For preliminary exploration and cleaning
- Power BI: For creating interactive dashboards and visuals

## 🧹 Data Cleaning
- Removed duplicates and missing values
- Encoded categorical variables
- Converted dates to proper datetime formats
- Created custom columns like stay duration and cancellation flag

## 📊 Key Visualizations (Power BI)
- Heatmaps: Cancellation rates by lead time and ADR  
- Bar Charts: Distribution of bookings by market segment, country  
- Line Charts: Booking trends across months/seasons  
- Treemaps: Room type preferences and special requests  
- KPI Cards: Cancellation %, Booking volume, Revenue estimates

## 🔍 Key Insights
- High lead time + high ADR = Increased chance of cancellation  
- City hotels showed more cancellations than resort hotels  
- Guests from certain countries had higher no-show rates  
- Peak seasons had both highest bookings and cancellations  
- Special requests correlated with longer stays and lower cancellations

## 💡 Recommendations
- Implement dynamic pricing for high lead-time bookings  
- Launch targeted campaigns for guests from high-cancellation regions  
- Offer incentives or reminders for confirmed bookings  
- Prioritize overbooking buffer during peak seasons

