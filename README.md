# case_study_purchase_data
Introduction This project focuses on analyzing a retail purchase dataset to uncover insights into customer behavior, product preferences, and demographic patterns. The analysis involves data exploration, visualization, and statistical testing to validate hypotheses about purchasing trends.

Table of Contents Introduction About the Dataset Data Exploration and Preparation Data Visualization Statistical Analysis One Sample Test for Mean One Sample Test for Proportion Two Sample Test for Means Two Sample Test for Proportions Evaluation Conclusion

About the Dataset The dataset used in this analysis contains detailed purchase records from a retail store. It includes 550,068 entries with the following features:

User_ID: Unique identifier for each user Product_ID: Unique identifier for each product Gender: Gender of the user Age: Age group of the user Occupation: Occupation code of the user City_Category: Category of the city Stay_In_Current_City_Years: Number of years the user has stayed in the current city Marital_Status: Marital status of the user Product_Category_1: Product category code 1 Product_Category_2: Product category code 2 Product_Category_3: Product category code 3 Purchase: Purchase amount

Data Exploration and Preparation

Loading Data: The dataset was loaded into a pandas DataFrame for inspection. Basic information about the dataset, such as the number of entries and data types of each column, was reviewed.

Handling Missing Values: Identified columns with missing values (Product_Category_2 and Product_Category_3). Dropped rows with missing values to clean the dataset.

Label Encoding: Converted categorical variables (e.g., Gender, Age, City_Category) into numerical format using label encoding.

Data Inspection: Reviewed the first few rows of the dataset to understand its structure and contents. Generated descriptive statistics to summarize the dataset.

Data Visualization

Bar Plots: Created bar plots to visualize the distribution of purchases by gender, age, and marital status. Analyzed the frequency of purchases across different product categories and occupations.

Count Plots: Generated count plots to examine the distribution of customers' stay in the current city and the purchase amount.

Correlation Heatmaps: Created heatmaps to visualize the correlation between different features using Spearman, Pearson, and Kendall methods.

Statistical Analysis

One Sample Test for Mean:

Tested if the average purchase made by men aged 18-25 is equal to 10000. Result: The mean purchase for this group is not 10000 (p-value < 0.05).

One Sample Test for Proportion:

Tested if the proportion of women spending more than 10000 is 35%. Result: The proportion is not 35% (p-value < 0.05).

Two Sample Test for Means:

Compared the average purchases between men and women aged 18-25. Result: The average purchases are not the same (p-value < 0.05).

Two Sample Test for Proportions:

Compared the percentage of men spending more than 10000 between age groups 18-25 and 26-35. Result: The percentages are the same (p-value > 0.05).

Evaluation The statistical tests conducted provided valuable insights into the purchasing behavior of different customer segments. Visualization techniques helped in understanding the distribution and relationships between various features. Data cleaning and preparation ensured that the analysis was based on a high-quality dataset.

Conclusion The analysis revealed significant patterns in customer behavior and product preferences. Key findings include:

Women make more frequent purchases than men. Customers aged 36-45 are the most active in making purchases. Product categories 1, 5, 2, and 3 are the most popular among customers. The average purchase amounts and proportions of spending differ significantly across gender and age groups. These insights can help the retail store in targeting specific customer segments and optimizing their product offerings and marketing strategies. The statistical tests validate the hypotheses, providing a solid foundation for making data-driven decisions.
