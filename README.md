# Hospitality-Analysis-Dashboard
## Recommended Structure and Order
### 1.	Hospitality Analysis Dashboard / *** AtliQ Grand Owns Multiple Five-Star Hotels Industry Across India****
A concise, descriptive name for the dashboard.
Example: 
❄️ Snowy Analytics: Hospitality Analysis Dashboard
A dynamic, interactive data visualization tool built to explore hotels' raw data for "AtliQ Grand's Owns multiple Five-Star Hotels across India", focusing on RevPar(revenue per available room), ADR(average daily rate), and Occupancy percentage, SRN(sellable room nights), DSRN(daily sellable room nights).

### 2.	Short Description / Purpose
1–2 sentences explaining what the dashboard does and why it exists.

Example: 
AtliQ Grands owns multiple five-star hotels across India. They have been in the hospitality Industry for the past 20 years.
Due to strategic moves from the other competitors and ineffective management decision-making, AtliQ Grand is losing its market share and revenue 
in the luxury/business hotels category. As a strategic move, the managing director of AtliQ Grands wanted to incorporate"Business and Data intelligence"
to regain their market share and revenue. However, they do not have an in-house data analytics team to provide them with these insights.

Their Revenue Management team had decided to hire a third-party service provider to provide them with insights from their historical data.
### 3.	Tech Stack
List the key technologies used to build the dashboard.

Example:
The dashboard was built using the following tools and technologies:<br>
•	📊 Power BI Desktop – Main data visualization platform used for report creation.<br>
•	📂 Power Query – Data transformation and cleaning layer for reshaping and preparing the data.<br>
•	🧠 DAX (Data Analysis Expressions) – Used for calculated measures, dynamic visuals, and conditional logic.<br>
•	📝 Data Modeling – Relationships established among tables (resorts, snow, and data_dictionary) to enable cross-filtering and aggregation.<br>
•	📁 File Format – .pbix for development and .png for dashboard previews.

### 4.	Data Source
More info on where the data comes from and how it’s structured
Example:
Source: from a particular YouTube channel for a data analytics project pulled from the zip file named "CodeBasics"

### 5.	Features / Highlights
The best dashboard explanation format. 
•	Business problem
•	Goal of the dashboard
•	Business impact & Insights

Example:
•	Business Problem
| Sno | Measures                  | Description                                                 |
| --- | ------------------------- | ----------------------------------------------------------- |
| 1   | Revenue                   | Sum of revenue\_realized                                    |
| 2   | Total Bookings            | Count of booking\_id in fact\_bookings                      |
| 3   | Average Rating            | Average of ratings\_given                                   |
| 4   | Total Capacity            | Sum of capacity                                             |
| 5   | Total Successful bookings | Sum of successful\_bookings from fact\_bookings             |
| 6   | Occupancy%                | Ratio of Total Successful Bookings to Total Capacity        |
| 7   | Total Cancelled Bookings  | Count of booking\_id in which booking\_status = "Cancelled" |
| 8   | Cancellation Rate         | Ratio of 'Total Cancelled Bookings' to 'Total Bookings'     |


Key questions such as:
Which regions offer the most family-friendly or expert-level skiing?
Where is summer skiing available?
What countries have the most well-equipped resorts?
… are difficult to answer quickly with raw data.

•	Goal of the Dashboard
We are going to filter the categories of required visualization, and also the goal of dashboard.
1. Filter by properties
2. Filter by city
3. Filter by status
4. Filter by platform
5. Filter by months
6. Filter by weeks

A stacked bar chart showing:
1. Card visualization chart
2. Line chart
3. Donut Chart
4. Stacked Column Chart
5. using Key Measures showing all the required columns and rows. 
•	Business Impact & Insights
 1. Revenue Performance Insight
Total Revenue: ₹90M generated, with the highest contributor being Atliq Bay (₹21M).
RevPAR (Revenue Per Available Room): ₹9.72K — a key profitability measure. Consistent performance indicates stable pricing and occupancy strategies.
Realisation %: 70.89% shows room for improvement in actual bookings versus sellable rooms. Better alignment of demand forecasting and pricing could raise this.
📊 2. Occupancy & Pricing Efficiency
Occupancy %: 57.37% across properties, with Atliq Blu and Atliq Bay leading in efficiency (>63%).
ADR (Average Daily Rate): ₹16.95K, steady across weeks (seen in the area chart), but RevPAR starts to dip post W20. This signals a drop in occupancy, not price cuts.
DSRN: 101 average daily sellable room nights, showing consistent inventory availability.
🧩 3. Property-wise Insights
Atliq Bay and Atliq City have higher average ratings (≥4.25), better occupancy, and strong revenue — ideal benchmark properties.
Atliq Exotica shows the lowest occupancy (45.48%) and average rating (3.09) — needs operational review or repositioning.
Cancellation Rate: Highest at Atliq City (23.87%) — potential issue with guest experience or overbooking practices.
📉 4. Trend Insights (Line & Area Chart)
Post week W20, RevPAR and Occupancy % decline significantly while ADR remains flat — suggests rooms are priced correctly, but demand dropped.
Calls for promotional offers, seasonal packages, or campaigns during those weeks to boost occupancy.
🧁 5. Category-Based Segmentation (Donut Chart)
Luxury category contributes ~60% of occupancy, compared to 56% from Business — suggesting that luxury rooms are more in demand.
Encourages focusing resources, services, and marketing towards the luxury segment for revenue maximization.
📱 6. Booking Platform Analysis
ADR and Realisation % are relatively even across platforms, but direct online channels appear slightly better.
Suggests investing more in own-brand promotions to reduce dependency on third-party platforms and improve margins.

✅ Actionable Recommendations
* Boost Occupancy in low-performing properties like Atliq Exotica via promotions or market repositioning.
* Analyze Customer Feedback for properties with low ratings (e.g., Atliq Palace, Exotica).
* Explore Dynamic Pricing for underperforming weeks to improve RevPAR.
* Leverage Top Channels like Direct Online & Tripstar with targeted campaigns.
* Focus on Luxury segment expansion given higher demand and revenue impact.

### 6.	Screenshots / Demos
Show what the dashboard looks like. - ![Alt text](https://github.com/username/repo/assets/image.png)
Example: ![Dashboard Preview]![image](https://github.com/user-attachments/assets/9a5f83e9-828f-4827-9058-0630d4ecf391)
