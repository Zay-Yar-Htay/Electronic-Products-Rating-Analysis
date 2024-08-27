# Electronic Products Data Ratings Analysis

## Table Of Contents

1. [Project Overview](#project-overview)
2. [Tools and Methodologies](#tools-and-methodologies)
3. [Business Questions](#business-questions)
4. [Visualization](#visualization)
5. [Insights and Recommendations](#insights-and-recommendations)


## Project Overview
This project focuses on analyzing the product dataset provided by Onyx Data to explore key factors influencing customer satisfaction, product recommendations, and the impact of product features on reviews and ratings. The dataset includes detailed attributes such as brand names, categories, colors, dimensions, and customer reviews, offering a rich source of information to explore how different factors influence product ratings and consumer behavior.

Key components of the dataset include:
* **Product Details:** Each product is meticulously cataloged, with information on brand, dimensions, color, and manufacturer.
* **Customer Reviews:** Extensive review data, including ratings, recommendation status, and review dates, allows for deep analysis.
* **Product Features:** Standardized features like color and dimensions enable consistent analysis across various products.

This project aimed to generate actionable insights that could guide product strategy, enhance customer satisfaction, and support data-driven decision-making in marketing and product development. The analysis focuses on answering key business questions, such as the relationship between product ratings and recommendations, identifying brands that lead in customer satisfaction, and understanding the impact of specific product features on customer reviews and ratings.


## Tools and Methodologies
To efficiently manage and analyze the product review data provided by Onyx, I utilized Power BI for data profiling, pre-processing, analysis, visualization, and reporting. The choice of Power BI was driven by the need for robust data handling, interactive reporting capabilities, and the ability to uncover key business insights. Below is a detailed breakdown of how the tool was employed throughout the project.

* **Data Profiling and Exploration**
  * Power BI was leveraged for initial data inspection and profiling. This step involved exploring the dataset to understand its structure, identifying data quality issues such as missing values or inconsistencies, and gaining an overall sense of the data before moving on to more detailed analysis.

* **Data Preprocessing**
  * Using Power BI's data transformation capabilities, including Power Query, the dataset was cleaned and prepared for analysis. This process involved handling missing values, converting values such as data decoding (converting quantitative to categorical transformation in rating attribute), and performing necessary transformations such as creating groups and hierarchies for product categories, features, etc.. to ensure the dataset was ready for analysis and visual purposes.

* **Data Analysis**
  * Conducted in-depth analysis directly within Power BI using DAX functions and custom measures to uncover patterns and relationships in the data. Key insights included exploring the relationship between product ratings and recommendation status, identifying top-performing brands, and analyzing the influence of product features on customer reviews.

* **Interactive Report Development**
  * Created visualizations, added slicers, and used DAX functions to build an interactive report that allowed end users to explore the data.
  * Developed reports that visualized key metrics such as average customer satisfaction, top-rated products, and feature-based analysis, providing a comprehensive view of the data.

* **Report Publishing**
  * Published the final report to Power BI Service, enabling users to access, interact with, and derive insights from the data.


## Business Questions
1. What is the relationship between product ratings and recommendation status?
2. Which brands have the highest average customer satisfaction, and how does it vary across different product categories?
3. How do product features (like color or dimensions) influence reviews and ratings?

## Visualization
![Electronic Products Rating Analysis Report](https://github.com/Zay-Yar-Htay/Electronic-Products-Rating-Analysis/assets/157587547/c632f6eb-49fe-4a20-a264-7496c8c8bdd7)


## Insights and Recommendations
**INSIGHTS**
* **Product Ratings and Recommendations:** Higher product ratings lead to more customer recommendations. For example, 5-star products are almost always recommended, while 2-star products rarely are. This shows that good ratings are key to getting customers to endorse a product.
* **Brand Performance in Customer Satisfaction:** Brands like CLARITY-TELEOM, Kicker, SVS, and Toshiba consistently make customers happy, with average ratings between 4.9 and 5.0. These brands do particularly well in areas like office appliances, audio, and electronics, showing their strong position in the market.
* **Influence of Product Color on Satisfaction:** The color of a product affects how satisfied customers are. Colors like "Black" and "Gray" usually get lower ratings, while "Cream" and "Blue" get higher ones. This suggests that color preferences might influence customer perceptions of quality or look.

**RECOMMENDATIONS**
* **Promote Top-Rated Products:** Emphasize products with 5-star ratings in marketing efforts, as they are most likely to be recommended by satisfied customers. Highlighting these products can enhance brand trust and encourage new purchases.
* **Improve Lower-Rated Products:** Focus on upgrading or revising products that receive lower ratings (2 stars or less). Improve Lower-Rated Products: Improving these products' quality or features could boost their ratings and recommendation rates.
* **Adjust Inventory Based on Color Preferences:** Consider expanding inventory for high-performing colors like "Cream" and "Blue," which have higher customer satisfaction. At the same time, consider reducing inventory for less popular colors like "Gray" to better align with customer preferences and improve overall satisfaction.
* **Strengthen Partnerships with High-Performing Brands:** Invest in promoting and expanding offerings from brands with high customer satisfaction, such as CLARITY-TELEOM, Kicker, SVS, and Toshiba. Their strong performance indicates a reliable market appeal, which can be leveraged to drive further growth.
