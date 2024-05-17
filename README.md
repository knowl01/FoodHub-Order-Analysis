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

# Data Overview
Here are the columns that are in the data;
* order id
* customer id
* restaurant name
* cuisine type
* cost
* day of the week
* rating
* food preparation time
* delivery time

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
