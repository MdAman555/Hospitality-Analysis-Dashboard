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
Due to strategic moves from the other competitors and ineffective decision-making in management, AtliQ Grand is losing its market share and revenue 
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
Source: from a particular YouTube channel for data analytics project pulled from the zip file named "CodeBasics"

### 5.	Features / Highlights
The best dashboard explanation format. 
•	Business problem
•	Goal of the dashboard
•	Walk-through of key visuals (briefly!)
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
•	Walkthrough of Key Visuals
-	Key KPIs (Top Left)
Total number of resorts: 499
Resorts with summer skiing: 29
Resorts with night skiing: 204
Child-friendly resorts: 495
Countries covered: 38
Continents represented: 5
-	Continent Filter Panel
An interactive slicer lets users filter all visuals by selected continents, such as Europe or Asia.
-	Top Countries with Most Resorts (Bar Chart)
Bar chart ranks countries like Austria, France, and the U.S. by number of ski resorts.
-	Slopes by Resort (Line Chart)
Displays the distribution of slope types (beginner, intermediate, expert, and total). Helps identify which resorts favor beginners vs. experts.
-	 Resorts by Skill Level (Dual Line Charts)
Two line visuals side by side: one for resorts that cater to beginners, another for experts—allowing skill-level segmentation.
-	Elevation Stats (Grouped Bar Chart)
Compare the highest and lowest elevation points of resorts to understand terrain steepness and potential snow quality.
-	Lift Types by Resort (Stacked Bar Chart)
A stacked bar chart showing:
1. Card visualization chart
2. Line chart
3. Donut Chart
4. Stacked Column Chart
5. using Key Measures showing all the required columns and rows. 

•	Business Impact & Insights


### 6.	Screenshots / Demos
Show what the dashboard looks like. - ![Alt text](https://github.com/username/repo/assets/image.png)
Example: ![Dashboard Preview]![image](https://github.com/user-attachments/assets/9a5f83e9-828f-4827-9058-0630d4ecf391)
