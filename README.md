# Walmart-Confidence-Interval-CLT
Walmart is an American multinational retail corporation that operates a chain of supercenters, discount departmental stores, and grocery stores from the United States. Walmart has more than 100 million customers worldwide.

## Business Problem:
1. The Management team at Walmart Inc. wants to analyze the customer purchase behavior (specifically, purchase amount) against the customer’s gender and the various other factors to help the business make better decisions. 
2. They want to understand if the spending habits differ between male and female customers: Do women spend more on Black Friday than men? (Assume 50 million customers are male and 50 million are female).

## Dataset Information:
The company collected the transactional data of customers who purchased products from the Walmart Stores during Black Friday.

### Source:
Please check the dataset at: "Dataset Link"

### Feature Information:
User_ID: User ID

Product_ID: Product ID

Gender: Sex of User(Male/Female)

Age: Age in bins

Occupation: Occupation(Masked)

City_Category: Category of the City (A,B,C)

StayInCurrentCityYears: Number of years stay in current city

Marital_Status: Marital Status

ProductCategory: Product Category (Masked)

Purchase: Purchase Amount
# Key Highlights:
#### Data Cleaning and Exploration:
1. Checked dataset structure and characteristics.
2. Detected null values and outliers using boxplot, describe method, and isnull function.
   
#### Data Exploration:
1. Calculated the average amount spent per transaction for male and female customers.
2. Inferred conclusions based on average spending for male and female customers.
3. Computed confidence intervals for average spending using the Central Limit Theorem.
4. Observed the distribution of mean expenses by changing the sample size.
   
#### Confidence Intervals:
1. Explored different confidence interval widths (e.g., 90%, 95%, 99%).
2. Determined if confidence intervals of average male and female spends overlap.

#### Analysis by Marital Status and Age:
1. Segmented customers based on marital status and age groups.
2. Analyzed spending patterns for married vs. unmarried customers and different age groups.

#### Recommendations:
1. Providing recommendations based on the insights gained from the analysis.
