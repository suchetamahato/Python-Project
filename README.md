# PRODUCT SALES DATA ANALYSIS WITH PYTHON

In this project, I followed a structured approach to data analysis, including data cleaning and visualization, to gain insights into the Product Sales Dataset. I effectively used Python libraries for data manipulation and visualization to present meaningful conclusions.

# Steps Followed

🔸**Importing Libraries**

The code starts by importing necessary Python libraries, including NumPy, Pandas, Matplotlib, and Seaborn for data analysis and visualization.

🔸**Loading Data**

It reads a CSV file ('Diwali Sales Dataset.csv') into a Pandas DataFrame ('df') using `pd.read_csv()`. It checks the shape, the first few rows, and general information about the dataset using `df.shape`, `df.head()`, and `df.info()`.

🔸**Data Cleaning**

I dropped Unrelated or unnecessary columns ('Status' and 'unnamed1') using `df.drop()`. I checked null values using `pd.isnull(df).sum()` and dropped using `df.dropna()`. I also converted data types, e.g., changing the 'Amount' column to integer using `.astype()`.

🔸**Data Exploration (EDA)**

Exploratory Data Analysis begins with a focus on different aspects of the dataset.

🔸**Gender Analysis**

Counts and total amounts are analyzed by gender, and bar plots are created. Insights are drawn about the gender distribution and purchasing power.

🔸**Age Analysis**

Counts and total amounts are analyzed by age group and gender, and bar plots are created. Insights are drawn about the age group distribution of buyers.

🔸**State Analysis**

Total orders and total sales are analyzed for the top 10 states. Bar plots provide insights into the most active states in terms of orders and sales.

🔸**Marital Status Analysis**

Counts are analyzed by marital status, and a bar plot is created. Insights are drawn about the marital status of buyers and their purchasing power, with a focus on gender.

🔸**Occupation Analysis**

Counts are analyzed by occupation, and a bar plot is created. Insights are drawn about the occupation distribution of buyers.

🔸**Product Category Analysis**

Counts are analyzed by product category, and a bar plot is created. Insights are drawn about the most sold product categories.

🔸**Top Sold Products**

The top 10 most sold products are identified and plotted using a bar plot.

# Insights

🔹Women are more active buyers compared to men [Orders- 69.87%, Amount/ Sales- 69.96%]

🔹Buyers of age group (26-35) years is maximum contributing [Orders- 40.70%, Amount/ Sales- 40.11%]

🔹Most of the total orders, and total sales/ amount are from Uttar Pradesh, Maharashtra, and Karnataka [Orders- 42.36%, Amount/ Sales- 44.55%]

🔹Most of the buyers are married [Orders- 58.05%, Amount/ Sales- 58.47%]

🔹Most of the buyers are working in the IT, Healthcare, and Aviation sector [Orders- 38.14%, Amount/ Sales- 38.02%]

🔹Most of the sold products are from the clothing, food, and electronics category [Orders- 64.20%, Amount/ Sales- 62.18%]

# Conclusion

🔎 **Gender**

Most of the buyers are females, and they have a higher purchasing power compared to men.

🔎 **Age**

The majority of buyers fall into the 26-35 years age group, and they are predominantly female.

🔎 **State**

The highest number of orders and total sales/amount are from Uttar Pradesh, Maharashtra, and Karnataka.

🔎 **Marital Status**

Married women are the most common buyers, and they tend to have a higher purchasing power.

🔎 **Occupation**

Most buyers work in the IT, Healthcare, and Aviation sectors.

🔎 **Product Category**

The most sold products are from the Food, Clothing, and Electronics categories.

These findings provide valuable insights into the characteristics of buyers and their preferences in the Product Sales Dataset. 

