# Pandas Challenge 

## Part 1: Exploring the Data
1. ***Import the Data:*** Start by importing the dataset from the provided CSV file.
2. ***View Column Names:*** Use Pandas to view the column names in the dataset.
3. ***Basic Statistics:*** Utilize the describe() function to gather some basic statistics about the dataset.
4. ***Data Exploration:*** Take the time to familiarize yourself with the data. Feel free to create additional cells as needed for exploration.

## Part 2: Transforming the Data
1. ***Calculate Subtotal:*** Create a new column that calculates the subtotal for each line using the unit price and quantity.
2. ***Calculate Shipping Price:*** Generate a new column for shipping price. Assume $7 per pound for orders over 50 pounds and $10 per pound for items 50 pounds or under.
3. ***Calculate Total Price:*** Create a new column for the total price using the subtotal, shipping price, and a sales tax of 9.25%.
4. ***Calculate Line Cost and Profit:*** Create columns for the cost of each line using unit cost, quantity, and shipping price, as well as the profit of each line using line cost and line price.

## Part 3: Validating the  Work
1. ***Verify Calculations:*** Confirm that the calculations match the provided email receipts for three orders, considering multiple lines per order.

## Part 4: Summarize and Analyze
1. ***Client Spending:*** Determine how much each of the top five clients by quantity spent.
2. ***Create Summary DataFrame:*** Generate a summary DataFrame for the top five clients, including total units purchased, total shipping price, total revenue, and total profit, sorted by total profit.
3. ***Format and Rename Columns:*** Format the data and rename columns to names suitable for presentation, with currency in millions of dollars.
4. ***Summary Findings:*** Write a brief 2-3 sentence summary of the key findings from the analysis.
