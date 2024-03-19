# pandas-challenge-1

## Requirements 
1. Explore the Data 

    View the column names.

    Use the describe function.

    Correctly identify the category with the most entries. 

    For the category with the most entries, correctly identify the subcategory with the most entries.

    Correctly identify the 5 clients with the most entries in the data.

    Store the client ids of those top 5 clients in a list.

    Display the total units (the qty column) that the client with the most entries ordered.

2. Transform the Data

    Create a column that calculates the subtotal for each line using the unit_price and the qty. 

    Create a column for shipping price. Assume a shipping price of $7 per pound for orders over 50 pounds and $10 per pound for items 50 pounds or under. 

    Create a column for the total price using the subtotal and the shipping price along with a sales tax of 9.25%. 

    Create a column for the cost of each line using unit cost, qty, and shipping price (assume the shipping cost is exactly what is charged to the client). 

    Create a column for the profit of each line using line cost and line price. 

3. Confirm Your Work
    Confirm that your calculations match the receipts. Remember, each order has multiple lines.

4. Summarize and Analyze
    How much did each of the top 5 clients by quantity spend? Use your work from Part 1 for client ids?
    
    Create a summary DataFrame showing the totals for the top 5 clients with the following information: total units purchased, total shipping price, total revenue, and total profit. Sort by total profit.
    
    Format the data and rename the columns to names suitable for presentation. Currency should be in millions of dollars.
    
    Write a brief 2-3 sentence summary of your findings.

## Results
    In this exercise, we were able to use the data to find that the top three categories of products were, Consumables, Furniture & Software. 
    By adding new columns, Subtotal, Shipping price, Total price, Line cost, & Line profit, we were able to calculate the spend amount, total units purchased, total shipping price, total revenue & total profit for the top 5 clients.   


## Resources used for this assignment 
 - Tutor Support
 - Xpert Chat  
 - Peer Support 
 - Class exercises
 
            