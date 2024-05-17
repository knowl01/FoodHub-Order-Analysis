# FoodHub-Order-Analysis: Project Overview
This project involves analyzing the data to get a fair idea about the demand of different restaurants which will help the company to enhance business and customer experience

# Course
Foundations of Data Science

**Skills and Tools covered**

* Exploratory Data Analysis
* Data visualization
* Statistics

# Code and Resources Used
 
 **Google Colab;** Jupyter Notebook
 
 **Packages:** Pandas, Numpy, matplotlib, seaborn

# Business Problem and Data Overview
The food aggregator company has stored the data of the different orders made by the registered customers in their online portal. They want toanalyze the data to get a fair idea about the demand of different restaurants which will help them in enhancing their customer experience. Perform the data analysis to fi nd answers to these questions that will help the company to improve the business.

**Dataset**

The detailed data dictionary is given below;

*  **order_id:** Unique ID of the order
*  **customer_id:** ID of the customer who ordered the food
*  **restaurant_name:** Name of the restaurant
* **cuisine_type:** Cuisine ordered by the customer
* **cost:** Cost of the order
* **day_of_the_week:** Indicates whether the order is placed on a weekday or weekend (The weekday is from Monday to Friday and theweekend is Saturday and Sunday)
* **rating:** Rating given by the customer out of 5
* **food_preparation_time:** Time (in minutes) taken by the restaurant to prepare the food. This is calculated by taking the difference betweenthe timestamps of the restaurant's order confi rmation and the delivery person's pick-up confirmation.
* **delivery_time:** Time (in minutes) taken by the delivery person to deliver the food package. This is calculated by taking the differencebetween the timestamps of the delivery person's pick-up confi rmation and drop-off information

 # Data Preprocessing
 The data needed to be cleaned and these are the following changes taht were made;
 1. Missing values treatment
 2. Correct data types
 3. Remove columns that had unique names for all rows.
 4. Remove duplicate rows
 5. Made columns for if differrent skills were listed in the job description;
       * Python
       * Excel

  # EDA
  I looked at the distribution of the data, value counts and unique values for various categorical variables. Below are the few highlights;

  **Statistical Analysis**

  ![Screenshot 2024-05-15 134508](https://github.com/knowl01/FoodHub-Order-Analysis/assets/135021827/050b7c22-73ec-4663-aacc-5cb3447626d0)
  
 # Univariate Analysis 
 
**Barplot for cuisine type**

<img width="677" alt="Screenshot 2024-05-17 184810" src="https://github.com/knowl01/FoodHub-Order-Analysis/assets/135021827/11d2a4f9-de35-4c85-88e3-eba1c5f78812">
  
# Multivariate Analysis

**Cuisine type vs Cost of the order**

<img width="682" alt="Screenshot 2024-05-17 185111" src="https://github.com/knowl01/FoodHub-Order-Analysis/assets/135021827/efb259cb-8fe8-421a-bed2-0b4cb8c15057">

**Correlation matrix of numerical variables**

<img width="643" alt="Screenshot 2024-05-17 185239" src="https://github.com/knowl01/FoodHub-Order-Analysis/assets/135021827/3f52c0ff-1063-4bd6-98fd-afdd9ac472b5">
