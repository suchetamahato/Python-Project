# PRODUCT SALES DATA ANALYSIS WITH PYTHON

This project follows a structured approach to data analysis, including data cleaning and visualization, to gain insights into the Diwali Sales Dataset. It effectively uses Python libraries for data manipulation and visualization to present meaningful conclusions.

# Steps Followed:

🔸**Importing Libraries**: The code starts by importing necessary Python libraries, including NumPy, Pandas, Matplotlib, and Seaborn for data analysis and visualization.

🔸**Loading Data**: It reads a CSV file ('Diwali Sales Dataset.csv') into a Pandas DataFrame ('df') using `pd.read_csv()`. It checks the shape, the first few rows, and general information about the dataset using `df.shape`, `df.head()`, and `df.info()`.

🔸**Data Cleaning**: Dropped Unrelated or unnecessary columns ('Status' and 'unnamed1') using `df.drop()`. I checked null values using `pd.isnull(df).sum()` and dropped using `df.dropna()`. I also converted data types, e.g., changing the 'Amount' column to integer using `.astype()`.

🔸**Data Exploration (EDA)**: Exploratory Data Analysis begins with a focus on different aspects of the dataset.

🔸**Gender Analysis**: Counts and total amounts are analyzed by gender, and bar plots are created. Insights are drawn about the gender distribution and purchasing power.

🔸**Age Analysis**: Counts and total amounts are analyzed by age group and gender, and bar plots are created. Insights are drawn about the age group distribution of buyers.

🔸**State Analysis**: Total orders and total sales are analyzed for the top 10 states. Bar plots provide insights into the most active states in terms of orders and sales.

🔸**Marital Status Analysis**: Counts are analyzed by marital status, and a bar plot is created. Insights are drawn about the marital status of buyers and their purchasing power, with a focus on gender.

🔸**Occupation Analysis**: Counts are analyzed by occupation, and a bar plot is created. Insights are drawn about the occupation distribution of buyers.

🔸**Product Category Analysis**: Counts are analyzed by product category, and a bar plot is created. Insights are drawn about the most sold product categories.

🔸**Top Sold Products**: The top 10 most sold products are identified and plotted using a bar plot.
