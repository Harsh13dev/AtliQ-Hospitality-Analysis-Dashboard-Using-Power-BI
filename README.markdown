# AtliQ Hospitality Analysis Dashboard

## Project Overview
This project involves the creation of a comprehensive Power BI dashboard for AtliQ Grands, a leading five-star hotel chain in India with over 20 years in the hospitality industry. The objective was to equip the revenue management team with actionable insights to address declining market share and revenue in the luxury/business hotel category due to competitive pressures and ineffective decision-making. The dashboard leverages data from multiple sources to provide a clear view of key performance metrics, enabling data-driven strategies to improve revenue and operational efficiency.

This project was developed as part of **CodeBasics Resume Project Challenge #1**.

## Problem Statement
AtliQ Grands is facing challenges in maintaining its market share and revenue in the luxury and business hotel categories. The goal was to create a Power BI dashboard that provides the revenue management team with valuable insights into revenue trends, occupancy rates, booking patterns, and customer satisfaction metrics to drive informed decision-making.

## Dataset
The dataset, sourced from the [CodeBasics website](https://codebasics.io/), consists of five CSV files:
- **dim_date**: Includes day type (weekend/weekday), month, and week number (W19–W32).
- **dim_hotels**: Contains property ID, property name, category (Luxury/Business), and city.
- **dim_rooms**: Includes room ID and room class.
- **fact_aggregated_bookings**: Stores booking details, including dates, platforms, number of guests, revenue, check-in, and checkout dates.
- **fact_bookings**: Includes successful bookings, hotel ID, and capacity.

## Key Insights
The Power BI dashboard visualizes the following insights for the period of May–July 2022:
- **Total Revenue**: ₹1.71 billion across all hotels.
- **Occupancy Rate**: 57.87%, with Delhi leading at 60.55%.
- **Average Rating**: 3.62 overall, with AtliQ Blu at 3.96 (highest) and AtliQ Seasons at 2.29 (lowest).
- **City Performance**:
  - Mumbai contributes 39.1% of revenue (₹669M).
  - Delhi contributes the least at 17.2% (₹295M) but has the highest occupancy (60.55%) and average rating (3.78).
- **Room Category Performance**:
  - Elite (RT2) rooms generate the highest revenue at ₹560.27M.
  - Average Daily Rates (ADR): Presidential (₹23.44K), Premium (₹15.12K), Elite (₹11.32K), Standard (₹8.05K).
  - Luxury category drives the majority of revenue and bookings.
- **Booking Trends**:
  - Total bookings: 134.59K.
  - Weekends show higher occupancy than weekdays, with no significant ADR difference.
  - Booking platforms: Other travel platforms contribute 40% of bookings and revenue, while direct offline bookings contribute the least (5%).
  - Direct offline bookings have a higher ADR compared to other platforms.
- **Correlation**: Hotels with higher ratings tend to generate more revenue.

## Dashboard Features
The Power BI dashboard includes:
- **Revenue Analysis**: Visualizations of total revenue, revenue by city, and revenue by room category.
- **Occupancy Trends**: Charts showing occupancy rates by city, property, and day type (weekend/weekday).
- **Booking Insights**: Breakdown of bookings by platform and room class.
- **Customer Satisfaction**: Average ratings by property and city, highlighting top and underperforming hotels.
- **Interactive Filters**: Allow users to filter by property, city, room class, booking status, and time period (May–July 2022).

## Technologies Used
- **Power BI**: For data visualization and dashboard creation.
- **Data Sources**: CSV files from CodeBasics.
- **Excel**: For initial data exploration and preprocessing.

## Project Structure
```
AtliQ-Hospitality-Analysis/
├── data/
│   ├── dim_date.csv
│   ├── dim_hotels.csv
│   ├── dim_rooms.csv
│   ├── fact_aggregated_bookings.csv
│   ├── fact_bookings.csv
├── AtliQ_Hospitality_Analysis.pbix
├── README.md
└── screenshots/
    ├── dashboard_overview.png
    ├── revenue_by_city.png
    ├── occupancy_trends.png
```

## How to Run the Project
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/AtliQ-Hospitality-Analysis.git
   ```
2. **Install Power BI Desktop**: Download and install [Power BI Desktop](https://powerbi.microsoft.com/desktop/) if not already installed.
3. **Open the Power BI File**: Open `AtliQ_Hospitality_Analysis.pbix` in Power BI Desktop.
4. **Explore the Dashboard**: Use the interactive filters to analyze revenue, occupancy, bookings, and ratings.
5. **Data Source**: The CSV files in the `data/` folder are already linked to the `.pbix` file. Ensure they remain in the same directory or update the data source paths in Power BI if necessary.

## Screenshots
*To be added: Screenshots of the dashboard will be included in the `screenshots/` folder to showcase key visualizations.*

## Key Recommendations
Based on the insights:
- **Improve Delhi Performance**: Despite high occupancy and ratings, Delhi’s revenue contribution is low. Explore pricing strategies or marketing campaigns to boost revenue.
- **Enhance AtliQ Seasons**: Address low ratings (2.29) through service improvements or customer feedback analysis.
- **Leverage Weekend Demand**: Capitalize on higher weekend occupancy with targeted promotions.
- **Optimize Booking Platforms**: Focus on increasing direct offline bookings to leverage higher ADR, while maintaining strong partnerships with travel platforms.
- **Promote Luxury Category**: Continue to emphasize Luxury rooms, which drive the majority of revenue.

## Future Enhancements
- Integrate real-time data feeds for dynamic updates.
- Add predictive analytics to forecast revenue and occupancy trends.
- Include customer segmentation to tailor marketing strategies.

## Contact
For questions or feedback, feel free to reach out via [GitHub Issues](https://github.com/your-username/AtliQ-Hospitality-Analysis/issues) or connect with me on [LinkedIn](https://www.linkedin.com/in/your-linkedin-profile/).