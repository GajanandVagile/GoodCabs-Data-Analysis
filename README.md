# Power BI & SQL Analysis - GoodCabs

## Problem Statement

**Domain:** Transportation & Mobility\
**Function:** Operations

Goodcabs, a cab service company established two years ago, has gained a strong foothold in the Indian market by focusing on tier-2 cities. Unlike other cab service providers, Goodcabs is committed to supporting local drivers, helping them make a sustainable living in their hometowns while ensuring excellent service to passengers. With operations in ten tier-2 cities across India, Goodcabs has set ambitious performance targets for 2024 to drive growth and improve passenger satisfaction.

As part of this initiative, the Goodcabs management team aims to assess the company's performance across key metrics, including trip volume, passenger satisfaction, repeat passenger rate, trip distribution, and the balance between new and repeat passengers.

However, the Chief of Operations, Bruce Haryali, wanted this immediately but the analytics manager Tony is engaged on another critical project. Tony decided to give this work to Peter Pandey who is the curious data analyst of Goodcabs. Since these insights will be directly reported to the Chief of Operations, Tony also provided some notes to Peter to support his work.

## Overview

This project analyzes ride-hailing trends for GoodCabs using SQL and Power BI. The goal is to extract key insights related to trip demand, passenger behavior, pricing efficiency, and seasonal trends.

## Key Insights

1. **Top and Bottom Performing Cities**

   - **Top 3 Cities:** Jaipur, Lucknow, Surat
   - **Bottom 3 Cities:** Vishakhapatnam, Coimbatore, Mysore

2. **Average Fare per Trip by City**

   - **Lowest Fare per Trip:** Surat, Lucknow (indicating potential underpricing)
   - **Highest Fare per Trip:** Jaipur, Kochi

3. **Average Ratings by City and Passenger Type**

   - **Highest Rated Cities:** Jaipur, Kochi
   - **Lowest Rated Cities:** Vadodara, Surat

4. **Peak and Low Demand Months by City**

   - **Peak Demand Months:** April, February, May
   - **Low Demand Months:** January, June

5. **Weekend vs. Weekday Trip Demand**

   - **Total Weekday Trips:** 238,338
   - **Total Weekend Trips:** 187,565

6. **Repeat Passenger Frequency Analysis**

   - **Cities with Highest Repeat Passenger Rate:** Surat, Lucknow
   - **Cities with Lowest Repeat Passenger Rate:** Mysore, Coimbatore (indicating low customer loyalty)

7. **Monthly Target Achievement Analysis**

   - **Cities Missing Trip Targets:** Lucknow&#x20;
   - **Cities Exceeding Trip Targets:** Jaipur

8. **Repeat Passenger Rate (RPR%) by City & Month**

   - **Highest RPR% Cities:** Surat, Lucknow
   - **Lowest RPR% Cities:** Mysore, Jaipur

## SQL Ad-hoc Analysis

1. **City-Level Fare and Trip Summary Report**

   - Generated a report displaying total trips, average fare per km, average fare per trip, and each city's percentage contribution to overall trips.

2. **Monthly City-Level Trips Target Performance Report**

   - Compared actual trips vs. target trips at the city and month level, categorizing performance as "Above Target" or "Below Target" with % difference calculations.

3. **Identify Cities with Highest and Lowest Total New Passengers**

   - **Top 3 Cities for New Passengers:** Jaipur, Kochi
   - **Bottom 3 Cities for New Passengers:** Coimbatore, Vadodara

4. **Identify Month with Highest Revenue for Each City**

   - Identified the highest revenue-generating month for each city based on total revenue trends.

5. **Repeat Passenger Rate Analysis**

   - Calculated monthly and overall repeat passenger rates to analyze customer retention.

## Tools & Technologies

- **SQL**: Data extraction and transformation.
- **Power BI**: Data visualization and dashboard creation.
- **Excel**: Data pre-processing.

## Project Links

- [GitHub Repository](https://github.com/your-username/PowerBI-SQL-Analysis-GoodCabs)
- [Power BI Dashboard Preview](https://app.powerbi.com/view?r=eyJrIjoiZTYyMzY1MGEtMTNjNS00MjYxLTg1MDgtMDUyMzdlNWNjOTRhIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)
- [Project Documentation](your-documentation-link)

## Future Enhancements

- Implement more dynamic filtering in Power BI.
- Automate data refresh using Power BI Service.
- Integrate with Python for advanced analysis.

## Contact

If you have any questions, feel free to connect with me on [LinkedIn](your-linkedin-profile-url).

