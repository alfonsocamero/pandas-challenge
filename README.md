# pandas-challenge
This script was written to read purchase data cointaining sales activity for a video game company. The scrip reads the csv file and provides the following information:

1. Total Number of players

2. Purchasing Analysis (Total)—number of unique items, average price, etc.

3. Gender Demographics
      Percentage and Count of Male Players
      Percentage and Count of Female Players
      Percentage and Count of Other / Non-Disclosed

4. Purchasing Analysis (Gender)—purchase count, avg. purchase price, avg. purchase total per person etc. by gender

5. Age Demographics—this part of the script:
      Establishes bins for ages
      Categorizes the existing players using the age bins
      Calculates the numbers and percentages by age group

6. Purchasing Analysis (Age)—this section of the script:
      Bins the purchase_data data frame by age and calculates purchase count, avg. purchase price, avg. purchase total per person etc
      
7. Top Spenders—extracts the top 5 spenders among all users

8. Most Popular Items—this section of the script retrieves certain columns, and performs a groupby to obtain purchase count, average item price, and total purchase value

9. Most Profitable Items—lastly, this section sorts the previoius dataframe by total purchase value in descending order to look at items in order of profitability. 
