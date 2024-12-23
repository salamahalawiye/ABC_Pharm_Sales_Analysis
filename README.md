# ABC_Pharm_Sales_Analysis
ABC Pharmaceutical Company operates in a highly competitive and regulated market, where understanding the dynamics of sales performance and customer purchasing behavior is crucial. Currently, the company struggles to integrate diverse data sources, and cannot perform granular analysis, leading to missed opportunities in targeting key customer segments and optimizing product distribution. This project aims to overcome the sales challenges by conducting a comprehensive data and geospatial analysis, revealing intricate patterns and correlations.

# Problem Statement
This analysis aimed at understanding the sales performance between different customer channels, sales variation in urban and rural areas, and the correlation between sales and product price.

# Tools Used
- Power BI 💼
- Microsoft Excel 📊
- Python
- DB Browser (SQLite)

# Skills Applied
- Data Cleaning and Preprocessing 🧹
- Exploratory Data Analysis (EDA) 📊
- Data Visualization 📈
- Statistical Analysis 📊
- Dashboard Design and Development 📊📈

# Methodology
- Data Acquisition: Data was provided from 3Signet.
- Data Cleaning: Cleanse the dataset to handle missing values, outliers, and inconsistencies.
- Exploratory Data Analysis (EDA): Conducted exploratory analysis to gain insights into the distribution and relationships between different variables.
- Visualization: Create visualizations using Power BI to communicate the findings and trends in the data effectively.
- Statistical Analysis: Performed statistical analysis to quantify the relationships between different variables and assess the significance against each other.
- Dashboard Creation: Develop interactive dashboards in Power BI to give users intuitive access to the insights generated from the analysis.
- Data Storytelling: Develop a story about all the insights generated on the report page.

# Dataset Schema
![image](https://github.com/user-attachments/assets/0facd7fd-1dde-4f44-ae7e-dd766213b735)

# Insights
- The total revenue across the 4 years is 12 billion (bn).
- Between 2017-2020, the year with the highest sales was 2018 (3.5bn) and the lowest sales occurred in 2020 (2bn).  The month with the highest sales collectively is November (1.1bn) and for the lowest sales, it is January (67m). 
- The top 3 product classes for each year by revenue are Analgesics (2.3bn), Antiseptics (2.2bn), and mood stabilizers (2bn).
- Germany accounted for 11bn (94%) of the revenue while Poland had only 680million (6%) in revenue.
- For Poland, sales were only recorded in 2018 and the highest class of drugs sold is antiseptics (6m) and mood stabilizers (2.6m) in November.
![image](https://github.com/user-attachments/assets/bc1536e2-9a10-4c64-ba92-222e9f3bb0b7)
![image](https://github.com/user-attachments/assets/98d0abbb-dec6-4a47-b7de-583fa4028467)
![image](https://github.com/user-attachments/assets/0d38347b-6312-4e1e-9f64-bb12bead9e66)
![image](https://github.com/user-attachments/assets/14d7aca0-d01d-4551-9553-3dcffb64b9b9)
![image](https://github.com/user-attachments/assets/6ea86230-82e6-4b92-8c7c-b78e84311107)

# Statistical Analysis
- This shows a positive correlation between the quantity of products and sales. There is also a positive correlation between the price of products and sales.
  
![image](https://github.com/user-attachments/assets/3735ba79-d2d2-4812-bc05-399432491a87)
![image](https://github.com/user-attachments/assets/ff96496c-5c32-4d07-a9ea-57723c1acc5e)

# Key Takeaways
- Sales depend on location as it plays a huge role in the class of drugs largely purchased in that vicinity.
- The Channel of distribution has an impact on revenue as analysis has shown Pharmacy have the highest revenue as compared to Hospitals. The same way government hospitals generate higher revenue as compared to private (the population is higher in government hospitals).
- Also, 94% of revenue is from Germany with the top cities being Altenburg, Cuxhaven, and Freidberg.
- The drug with the highest revenue is Sumanazole (113m) and the least is Ampheslox (2.6m).
- Urban settlements account for the majority of the top products in comparison to rural locations.


# Recommendations:
- Leverage the data obtained on classes of drugs based on location during the distribution process. Antiseptics are highly purchased in Ludwigshafen as compared to Bottrop. Also, analgesics and antiseptics are common in urban areas. Distribution should be prioritized to these fast-moving locations as compared to the slow-moving ones.
- Retail pharmacies and public hospitals should be the priority during distribution, a bulk of the revenue comes from both location.
- Implement strategies by Brittany Bold and her team members, which account for the bulk of revenue made. Incentives can be given to Brittany Bold’s team to encourage them and motivate other managers and their team members to do better in their locations.



