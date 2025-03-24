# IISER Food Delivery Analysis

## Description
This project analyzes food and grocery delivery data collected at the Indian Institute of Science Education and Research Pune (IISER Pune). The analysis focuses on understanding delivery service usage patterns across different platforms (Swiggy, Zomato, etc.) and time periods to gain insights into food ordering behaviors within the campus community.

## Dataset
The project uses three CSV files with hourly delivery service data:
Contains basic delivery data with columns for time and different delivery services.

Each file tracks the number of deliveries per hour from various services:
- Food delivery: Swiggy, Zomato, Eatsure, Eatclub, Dominoz
- Grocery/essentials: BigBasket, Dunzo, Zepto, Blinkit
- Others: Miscellaneous delivery services
- Total deliveries: Sum of all deliveries in the hour

The data spans from October 15, 2022, with hourly records.

## Analysis Components
The notebook `delivery_Data.ipynb` performs the following analyses:

1. **Data Loading and Preprocessing**
   - Loading the CSV dataset
   - Setting datetime as index
   - Basic data validation and cleaning

2. **Temporal Analysis**
   - Hourly delivery patterns
   - Daily trends (weekday vs weekend differences)
   - Weekly patterns
   - Service usage distribution by time of day

3. **Service Comparison**
   - Market share of different delivery platforms
   - Platform popularity at different times
   - Correlation between services

4. **Statistical Analysis**
   - Descriptive statistics for each delivery service
   - Peak delivery times identification
   - Trend analysis over the data collection period

## Requirements
- Python 3.8
- pandas
- numpy
- matplotlib
- seaborn

Run the cells sequentially to perform the analysis

## Key Findings
The analysis provides insights into:
- Peak delivery hours on campus
- Most popular delivery services among IISER Pune community
- Day-of-week patterns in food ordering
- Changes in delivery service usage over time
- Comparative analysis of food v/s grocery delivery services

## Visualizations
The notebook generates various visualizations:
- Time series plots showing delivery patterns by hour and day
- Bar charts comparing delivery service usage
- Heatmaps showing service correlations
- Day-of-week analysis showing when most deliveries occur

## Applications
This analysis can be helpful for:
- Campus food service planning
- Understanding student food preferences and behaviors
- Delivery service companies targeting campus communities
- Campus infrastructure planning (delivery management, traffic flow)

## Limitations
- The dataset is limited to the specific time period collected
- Only represents delivery patterns at IISER Pune, may not be generalizable
- No demographic information about who is ordering

## Future Work
- Incorporate demographic data for more detailed analysis
- Expand data collection to longer time periods
- Include pricing information to analyze spending patterns
- Geographic analysis of delivery locations within campus

*Note: This README provides an overview of the IISER Pune food delivery analysis project. For detailed methods and findings, please refer to the notebook itself.* 
