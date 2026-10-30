Uber Ride Analytics Dashboard | Power BI
An interactive Power BI dashboard built to analyze Uber ride
bookings, booking performance, revenue, distance, vehicle usage, and
customer/driver ratings. The dashboard provides a high-level view of
ride operations across the year, with monthly trends and location-level
insights.
DashBoard Preview:
<img width="1320" height="732" alt="image" src="https://github.com/user-attachments/assets/4d0eb7e8-df97-472f-a3b1-c63fc9501ac9" />


Project Objectives
- Monitor completed, incomplete, and cancelled bookings.
- Compare booking value and completed bookings month by month.
- Track total revenue and total ride distance.
- Understand booking value by vehicle type.
- Identify popular pickup and drop locations.
- Review customer and driver ratings.
Dashboard KPIs
The following values are displayed in the dashboard screenshot:

  KPI                    Displayed value
  Completed Bookings                 93K
Lost Bookings                      57K
Total Revenue                      52M
Total Distance                   2.51M
Average Distance                 24.64
Driver Ratings                 393.48K
Customer Ratings               409.63K

The booking-status summary also displays: - Complete: 93K -
Incomplete: 19K - Cancelled: 37K

Values are shown as displayed in the dashboard and may be rounded by
Power BI formatting.
Dashboard Features
1. Booking and revenue overview
- KPI cards for completed bookings, lost bookings, total revenue,
  total distance, and average distance.
- Monthly booking-value column chart.
- Monthly completed-bookings trend.
2. Booking status analysis
- Donut charts for completed, incomplete, and cancelled bookings.
- Monthly comparison of lost bookings and total bookings.
3. Vehicle-type analysis
- Horizontal bar chart showing booking value by vehicle type,
  including Auto, Bike, Go Mini, Go Sedan, Premier Sedan, and Uber XL.
4. Location analysis
- Pickup location summary.
- Drop location summary.
- Completed booking counts by location.
5. Ratings
- Driver ratings.
- Customer ratings.
Tools & Technologies
- Microsoft Power BI Desktop --- dashboard development and
  visualization.
- Power Query --- data import and transformation (if used in the
  project).
- DAX --- measures and KPI calculations (if used in the project).
- Microsoft Excel --- source data file.
Repository Contents
A suggested GitHub repository structure:
uber-ride-analytics/
│
├── README.md
├── dashboard-preview.png
├── Uber-Ride-Analytics.pbix
└── data/
    └── uber.xlsx
Only include files you are comfortable making public. If the dataset
contains personal, confidential, or licensed information, do not upload
it; share an anonymized or permitted sample instead.
How to View the Dashboard
1. Download or clone this repository.
2. Open Uber-Ride-Analytics.pbix using Power BI Desktop.
3. If prompted, update the data source path to the location of the
   Excel file.
4. Refresh the data.
5. Explore the dashboard using the available date and category
   controls.
Suggested GitHub Repository Description
Power BI dashboard for analyzing Uber ride bookings, revenue, distance, vehicle types, booking status, locations, and customer/driver ratings.
Future Improvements
- Add customer-level ride frequency and repeat-customer analysis.
- Analyze customer and driver cancellation reasons.
- Add date, vehicle type, payment method, and booking-status slicers.
- Compare booking trends across quarters and weekdays.
- Add top and bottom pickup/drop locations.
- Include cancellation and completion rates as percentage KPIs.
Author
Princy Patel

BCA Student | Aspiring Data Analyst
If you find this project useful, feel free to star the repository.
