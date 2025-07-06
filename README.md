# DSA-CAPSTONE-PROJECT-1
My DSA Project on Excel
## Table of Content
### Project Overview
### Data Source
### Tools Used
### Analytical Approach
### Result and Insight
### Conclusion


### Project Overview
This project is aimed at analysing product and customer review data from **Amazon** to generate insights that can guide product improvement, marketing strategies, and customer engagement. As a Junior Data Analyst at RetailTech Insights, i'm expected to work on the data so that the company can know what is working, what is not working and things to focus on in the organisation.
### Data Source
The data source for this pjroject was shared with all registered student of DSA by **The Incubator Hub** of which i'm one. This source is an excel file.
### Tools Used
Microsoft Excel [Download Here](https://www.microsoft.com/en/microsoft-365/excel)
 - For data cleaning
 - For data exploration and analysis
 - For Data visualisation\
### Analytical Approach
- Understanding of Project demands
- Understanding of Given Data
- Data Cleaning and Transformation
- Data Exploration and Analysis
- Data Visualisation
#### Understanding of Project demands
Before commencing the analysis, I took time to fully and properly understand what the project is all about and what i'm expected to do as a Junior Data Analyst. This is very vital to my analysis because it helps me to know where i'm going to and how to help the business achieve their aim.
![1 to be](https://github.com/user-attachments/assets/776677cd-8d42-41a8-bc43-51a89c053b04)
![2 to be](https://github.com/user-attachments/assets/e80d5912-bf1f-406e-86e9-356f68bdbe1a)


#### Understanding of Given Data
The next thing i did after understanding the project demands, I  took a close study of the given data. I took time to study and understand the given data which help me know how to clean, explore and visualise the data properly.

![image](https://github.com/user-attachments/assets/375c62ce-2459-4a86-9ba5-d6f4d81a5985)
#### Data Cleaning and Transformation
In this stage i was able to do the following:
 - Changing of column header to upper case using upper function.
 - Using the remove column duplicate button in the data tools group under the under the data tab, I was able to remove products with duplicated PRODUCT_ID to avoid error in my analysis.
 - Creation of another column for category to avoid too long category names using insert option, left function and find function. Then I was now able to use only the first category of each cell as my category.
 - Removal of a row because of the wrong syntax it contains instead of numbers and imputation of zero in two blank cells instead of leaving it blank. This decision was because there is no one that could provide the missing details.
 - Creation of potential revenue column using actual_price *review_count
 - Correction of column containing numerical value as text by changing the data type to number
 - Creation of new column called “DISCOUNT RANGE” to evaluate the question of counting  products with 50% discount or more
 - Creation of new column called “PRICE RANGE BUCKET” to address the question of unique product per price range
#### Data Exploration and Analysis
Under this step I was able to put answers to the following questions using pivot table:
 1. What is the average discount percentage by product category? 
 2. How many products are listed under each category? 
 3. What is the total number of reviews per category?  
 4. Which products have the highest average ratings? 
 5. What is the average actual price vs the discounted price by category? 
 6. Which products have the highest number of reviews? 
 7. How many products have a discount of 50% or more? 
 8. What is the distribution of product ratings (e.g., how many products are rated 3.0, 
4.0, etc.)? 
 9. What is the total potential revenue (actual_price × rating_count) by category? 
 10. What is the number of unique products per price range bucket (e.g., <₹200, 
₹200–₹500, >₹500)? 
 11. How does the rating relate to the level of discount? 
 12. How many products have fewer than 1,000 reviews? 
 13. Which categories have products with the highest discounts? 
 14. Identify the top 5 products in terms of rating and number of reviews combined.

![STANDARD 1](https://github.com/user-attachments/assets/7dfc97c1-eeba-4eee-8dde-f734aa50423d)

![STANDARD 2](https://github.com/user-attachments/assets/edc1961d-7546-4dc3-adba-740d5f4022a8)


#### Data Visualisation
using the visualization cats and bars, I was able to produce a visual representation of my analysis which displayed some essential exploratory information.

![ACTUAL 2](https://github.com/user-attachments/assets/8fa80956-e343-4a92-b074-0697d3e9b8b6)


### RESULT AND CONCLUSION
My analysis shows that the category **Electronics** have the highest sales and review and this can be due to the fact that electronics have a significant percentage of discount.

![i need it](https://github.com/user-attachments/assets/d40684de-c6a6-4d44-9e09-0ea1b43f546f)

Also, it is expressly seen that the category **Toys and Games** is not selling which can be due to the fact that it has no discount at all and this may eventually make customers to buy from other companies whose Toys and Games seem lesser to them.

### Recommendation
I would therefore recommend that **Amazon** should look into how they can discount the price of **Toys and Games** so that the sales of this category of product can increase.






