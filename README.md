# Tableau Airbnb Analysis
## Table of Contents

1. [Project Overview](#project-overview)  
2. [Data Source](#data-source)  
3. [Tools Used](#tools-used)  
4. [Data Cleaning & Preparation](#data-cleaning--preparation)  
5. [Exploratory Data Analysis](#exploratory-data-analysis)  
   - [Pricing and Revenue](#pricing-and-revenue)  
   - [Room Type Insights](#room-type-insights)  
   - [Availability & Seasonality](#availability--seasonality)  
6. [Results / Key Insights](#results--key-insights)  
   - [Pricing and Revenue](#pricing-and-revenue-1)  
   - [Room Type Insights](#room-type-insights-1)  
   - [Availability & Seasonality](#availability--seasonality-1)  
7. [Recommendations](#recommendations)  
   - [Pricing Optimization](#pricing-optimization)  
   - [Inventory and Room Type Strategy](#inventory-and-room-type-strategy)  
   - [Neighborhood Focus](#neighborhood-focus)  
   - [Seasonality Planning](#seasonality-planning)  
   - [Data Monitoring & Continuous Improvement](#data-monitoring--continuous-improvement)  
8. [Limitations](#limitations)  
9. [References](#references)

## Project Overview

This data visualization project aims to provide insight into the Airbnb market by exploring listings, pricing trends, neighborhood performance, and host activity. By analyzing these factors, the project seeks to identify patterns in pricing, availability, and reviews, offering a deeper understanding of the factors that influence listing performance. The interactive Tableau dashboard allows users to explore the data visually, uncover trends, and gain actionable insights into the Airbnb ecosystem.

## Data Source

- **Airbnb Listings 2016 Dataset** — Alexander Freberg, Kaggle: https://www.kaggle.com/datasets/alexanderfreberg/airbnb-listings-2016-dataset
## Tools Used

- **Tableau Public** – Used to clean, analyze, and visualize the Airbnb dataset and create interactive dashboards.
- **Microsoft Excel** – For initial data cleaning and formatting before importing into Tableau.
- **Kaggle** – Source of the Airbnb 2016 dataset.
- **Git & GitHub** – Version control and repository hosting.
## Data Cleaning & Preparation

Before visualizing the Airbnb dataset in Tableau, the data underwent several preparation steps to ensure accuracy and usability:

1. **Handling Missing Values:**  
   - Identified and addressed missing or null values in key columns such as `price`, `neighborhood`, and `room_type`.  
   - Replaced missing numerical values with appropriate defaults or removed incomplete records when necessary.

2. **Data Formatting:**  
   - Standardized date formats and numerical fields for consistency.  
   - Converted price fields to numeric values by removing currency symbols and commas.

3. **Filtering & Subsetting:**  
   - Removed duplicate listings and outliers that could skew analysis (e.g., extreme prices).  
   - Focused on relevant variables for analysis, such as `neighborhood`, `room_type`, `price`, `availability`, and `review_scores`.

These steps ensured the dataset was clean, structured, and ready for meaningful visualization in Tableau dashboards.
## Exploratory Data Analysis

The Tableau dashboards were designed to answer questions a client might have about their Airbnb business:

1. **Pricing and Revenue**
   - Which neighborhoods or ZIP codes have the highest and lowest prices?  
   - How does price vary by room type?

<img width="1289" height="761" alt="Screenshot 2025-12-10 220322" src="https://github.com/user-attachments/assets/44e0df63-c0b8-439c-82e7-9a377f35c207" />

2. **Room Type Insights**
   - Which types of Rentals (number of bedrooms) are most common?  
   - How do different room types affect pricing?
<img width="705" height="351" alt="Screenshot 2025-12-10 220643" src="https://github.com/user-attachments/assets/81b62ff1-587b-46d0-b8ed-f7ffde90ef70" />

3. **Availability & Seasonality**
   - Which listings are available year-round vs. seasonally?  
<img width="1309" height="750" alt="Screenshot 2025-12-10 220724" src="https://github.com/user-attachments/assets/04cde943-f941-4347-81ea-4d581e63394e" />

These questions provide a **business-oriented framework** for your Tableau dashboards, ensuring the visualizations help the client make **data-driven decisions** about pricing, marketing, and property management.

## Results / Key Insights

Based on the Tableau dashboards, the following insights answer the potential client questions:

1. **Pricing and Revenue**
   - The average listing price is highest in **98134** and lowest in **98125**.   
   - A few extreme listings were identified as outliers, which could skew overall averages.


2. **Room Type Insights**
   - One Bedrooms make up approximately **70.19%** of listings, two bedrooms **18.72%**, and three bedrooms **7.98%**.  
   - Room type impacts pricing and availability, with one bedrooms being cheaper and less frequently available.


3. **Availability & Seasonality**
   - Many listings are available year-round, but some show seasonal patterns, with peak availability during **the end of the year holiday's and Summer months**.  
   - Availability varies by neighborhood, helping identify high-demand periods and underutilized listings.

**Overall**, the dashboards provide actionable insights that can help the client:

- Optimize pricing strategies by neighborhood and room type  
- Identify high-performing and underperforming areas  
- Make data-driven decisions about property investment and marketing strategies

## Recommendations

Based on the cleaned data, EDA, and insights from the Tableau dashboards, the following recommendations are suggested for the client:

1. **Pricing Optimization**
   - Consider adjusting prices in neighborhoods with high demand and occupancy, such as **98134**, to maximize revenue.  
   - Monitor outlier listings with extremely high or low prices to ensure they are aligned with market standards and do not distort overall pricing strategies.  
   - Implement dynamic pricing strategies for seasonal peaks, particularly during **end-of-year holidays and summer months**.

2. **Inventory and Room Type Strategy**
   - Since **one-bedroom listings make up the majority of the market (70.19%)**, consider diversifying property offerings with two or three-bedroom rentals to capture underserved segments.  
   - Adjust marketing and pricing strategies based on room type: one-bedroom units may attract budget-conscious travelers, while larger units can target families or groups willing to pay more.

3. **Neighborhood Focus**
   - Target marketing efforts in neighborhoods with lower availability, such as **98125**, to increase occupancy and visibility.  
   - Evaluate high-performing neighborhoods for potential expansion of listings or promotional campaigns.

4. **Seasonality Planning**
   - Prepare for peak demand during **holidays and summer months** by offering special promotions or dynamic pricing adjustments.  
   - Encourage hosts to make more properties available year-round where feasible to reduce seasonal gaps in occupancy.

5. **Data Monitoring & Continuous Improvement**
   - Continuously track metrics such as price, occupancy, and review scores to identify trends and adjust strategies in real-time.  
   - Maintain data quality by regularly checking for missing values, outliers, or inconsistencies to ensure dashboards remain reliable for decision-making.

**Overall**, implementing these recommendations can help the client **maximize revenue, improve occupancy, and target growth opportunities**, while leveraging the insights revealed in the Airbnb Tableau dashboards.
## Limitations

While the Airbnb Tableau project provides valuable insights, several limitations should be considered:

1. **Data Age and Coverage**  
   - The dataset is from **2016**, which may not reflect current market conditions, pricing trends, or occupancy patterns.  
   - Only listings present in the dataset are analyzed; newer listings or changes in neighborhoods are not captured.


2. **Room Type and Property Details**  
   - The dataset primarily categorizes by room type and number of bedrooms; other factors influencing price and occupancy (e.g., amenities, property condition) are not fully captured.  

3. **Seasonality and External Factors**  
   - While seasonal patterns were observed, external factors such as local events, economic changes, or regulatory shifts are not included in the dataset.  
## References
 **Airbnb 2016 Listings Dataset**  
   - Alexander Freberg, Kaggle: [https://www.kaggle.com/datasets/alexanderfreberg/airbnb-listings-2016-dataset](https://www.kaggle.com/datasets/alexanderfreberg/airbnb-listings-2016-dataset)



