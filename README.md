🚖 Ola Booking Analysis Dashboard | Power BI
A comprehensive Power BI Dashboard built to analyze Ola ride booking data. It turns raw booking records into interactive insights on booking trends, revenue, vehicle performance, cancellations, and customer & driver ratings — enabling data-driven business decisions.

📅 Analysis period: 01 July 2024 – 30 July 2024

📌 Project Overview
This project analyzes Ola booking data using Microsoft Power BI. The report transforms raw booking information into interactive visualizations that reveal customer behavior, operational efficiency, revenue trends, and service quality.

The dashboard has five interactive pages, each focusing on a different business aspect.

📊 Dashboard Pages
1️⃣ Overall Analysis
A complete overview of booking performance.

Key Metrics: Total Bookings · Total Booking Value · Ride Volume Over Time · Booking Status Distribution · Date-wise Filtering

Key Insights (selected period):

49 total bookings worth ₹18K in booking value
67.35% success rate (33 successful rides)
Failures split across Canceled by Driver (18.37%), Driver Not Found (8.16%), and Canceled by Customer (6.12%)
Ride volume is spiky, peaking at 5 rides/day around 21 Jul
Overall Analysis

2️⃣ Vehicle Type Analysis
Analyzes customer preference and performance across vehicle categories.

Metrics: Vehicle Type · Total Booking Value · Success Booking Value · Avg. Distance Travelled · Total Distance Travelled

Key Insights:

E-Bike leads on total booking value (6,575) and total distance (173 km)
Prime Plus (5,486) and Prime SUV (5,292) follow closely on revenue
Mini (33.8) and E-Bike (34.6) record the highest average trip distance
Auto has the shortest average trips (5.0 km) and lowest success value
Vehicle Type Analysis

3️⃣ Revenue Analysis
Focuses on revenue generation, payment behavior, and top customers.

Metrics: Revenue by Payment Method · Ride Distance Timeline · Customer-wise Booking Value · Payment History

Key Insights:

Cash is the dominant payment method (>₹10K), followed by UPI (~₹5K) and a small Credit Card share
Total customer booking value: 28,012
Top customer: CID810214 (2,183), then CID902781 (2,014)
Revenue Analysis

4️⃣ Cancellation Analysis
Detailed insight into cancelled rides and their reasons.

Metrics: Total Bookings · Successful Bookings · Cancelled Bookings · Customer Cancellation Reasons · Driver Cancellation Reasons

Key Insights:

12 of 49 bookings were cancelled (33 successful)
Customer cancellations: 66.67% "Driver is not moving towards location", 33.33% "Driver asked to cancel"
Driver cancellations: 44.44% "Personal & Car related issue", 33.33% "Customer related issue", 22.22% "Customer was coughing/sick"
Cancellation Analysis

5️⃣ Ratings Analysis
Evaluates customer satisfaction and driver performance by vehicle type.

Metrics: Driver Rating by Vehicle Type · Customer Rating by Vehicle Type

Key Insights:

Best driver ratings: E-Bike (4.44) and Mini (4.12); Auto is lowest (3.15)
Best customer ratings: Auto (4.65) and Prime SUV (4.18)
Ratings reveal a gap between driver and customer satisfaction across categories
Ratings Analysis

🛠️ Tools & Technologies
Microsoft Power BI
Power Query (data cleaning & transformation)
DAX (Data Analysis Expressions)
Data Modeling
Interactive Visualizations
📊 Features
Interactive dashboard navigation · Dynamic date filtering · KPI cards · Pie / bar / line charts · Matrix tables · Drill-down analysis · Cross filtering · Business insights

📁 Repository Structure
Ola-Booking-Analysis/

│
├── README.md

├── LICENSE

├── Dashboard/

│   └── Ola Booking.pbix          # Power BI report file

├── Dataset/

│   └── Ola_Booking_Data.xlsx     # Source dataset

├── Images/

│   ├── overall.png

│   ├── vehicle.png

│   ├── revenue.png

│   ├── cancellation.png

│   └── ratings.png

└── docs/
    └── dashboard_overview.pdf     # All 5 pages exported to PDF
    
📌 Business Questions Answered
How many bookings were made during the selected period, and what is their total value?
What is the overall booking success rate?
Which vehicle type generates the highest revenue and covers the most distance?
Which payment method is used the most?
Who are the highest-value customers?
What are the major reasons behind customer and driver cancellations?
Which vehicle type earns the best customer and driver ratings?
How does ride volume change over time?
📈 Key Dashboard KPIs
Total Bookings · Successful Bookings · Cancelled Bookings · Booking Value · Revenue · Ride Volume · Payment Methods · Vehicle Performance · Customer Ratings · Driver Ratings · Average Distance Travelled

💡 Project Highlights
✔ Interactive, multi-page Power BI dashboard ✔ End-to-end booking analysis ✔ Revenue & payment insights ✔ Vehicle performance analysis ✔ Cancellation reason tracking ✔ Customer & driver rating analysis ✔ Dynamic date filtering & KPI monitoring

🚀 Future Improvements
Real-time dashboard integration · Predictive booking analysis · Revenue forecasting · Customer segmentation · Geographical ride analysis · Peak-hour demand prediction

👨‍💻 Author
Tejus Pandey

LinkedIn: https://www.linkedin.com/in/tejuspandey
GitHub: https://github.com/tejus23
⭐ If you found this project useful, consider giving it a star!
