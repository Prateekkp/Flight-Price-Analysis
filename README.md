# Flight Price Analysis Project

## Background and Overview
With air travel becoming increasingly popular, understanding flight pricing dynamics and customer preferences has become essential. This project aims to analyze flight data to derive actionable insights about fare structures, airline operations, and travel preferences. The dataset, sourced from Goibibo, covers various attributes such as price, airline, stops, and flight duration, enabling a deep dive into the industry patterns.

## Data Structure Overview
The dataset includes the following columns:
- **flight_date**: Date of the flight.
- **airline**: The airline operating the flight.
- **flight_num**: Unique flight number identifier.
- **class**: Flight class (e.g., Economy, Business).
- **from**: Departure location.
- **dep_time**: Departure time.
- **to**: Arrival location.
- **arr_time**: Arrival time.
- **duration**: Flight duration.
- **price**: Flight fare.
- **stops**: Number of stops (e.g., 0 for non-stop, 1 for one-stop).

Data Cleaning Steps:
- Converted relevant columns to appropriate data types.
- Removed leading and trailing whitespaces.
- Converted `stops` data to numerical values for analysis.

## Executive Summary
My analysis revealed key trends in the flight data:
1. **Price Distribution**: A significant number of flights (over 100,000) are priced below ₹10,000, indicating a market trend towards affordable options.
2. **Flight Operations by Airline**: Vistara operates the highest number of flights, followed by Air India and Indigo, showcasing a dominant market presence.
3. **Class Preferences**: Economy class remains the most popular choice, with Business class usage being about half of Economy.
4. **Price by Airline**: Vistara has the highest average ticket price (~₹30,000), while Indigo and TruJet offer more economical fares, with TruJet being the most budget-friendly.
5. **Flight Stop Frequency**: Most flights have one stop, indicating that travelers are often willing to accept layovers for reduced fares.

## Insights Deep Dive
### 1. Price Distribution Analysis
*Visualization of flight prices to understand the frequency and spread of budget vs. premium fares.*

### 2. Airline Operations
*Bar chart of flights operated by each airline.*

### 3. Class Preferences
*Pie chart depicting the proportion of travelers choosing Economy vs. Business class.*

### 4. Price by Airline
*Comparison of average ticket prices by airline, showcasing cost variations.*

### 5. Stops Analysis
*Histogram of stop frequencies across flights.*

> **Note**: Add screenshots or visualizations generated during analysis in the spaces provided.

## Recommendations
Based on the findings:
1. **Airline Pricing Strategy**: Airlines with higher average fares could explore promotional discounts or loyalty programs to attract budget-conscious travelers.
2. **Class Offerings**: Expanding Economy class offerings could better meet demand while maintaining a premium segment for Business class.
3. **Stopover Optimization**: Airlines with multi-stop routes could consider direct options on popular routes, balancing affordability and traveler preferences.
4. **Customer Segmentation**: Airlines might benefit from targeting frequent Economy travelers with upgrades or additional services.

## Conclusion
The analysis highlights the competitive pricing strategies in the airline industry, along with customer preferences for affordable and non-stop flights. By optimizing their offerings, airlines can cater to the evolving needs of travelers, maximizing both revenue and customer satisfaction. This project provides a baseline for future research on flight pricing trends and customer behavior in the airline sector.

---

## Repository Contents
- **data**: The raw and processed flight data files.
- **notebooks**: Jupyter notebooks containing the EDA and insights generation code.
- **visuals**: Folder for visualizations generated during analysis.
- **README.md**: Project documentation and overview (this file).
