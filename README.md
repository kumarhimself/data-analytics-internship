# Data Analytics Internship Exercise
#### Ayush Kumar

## Part 1: Creating a Structured Relational Data Model
Check the png file `relational-diagram.drawio.png` in the repository

## Part 2: Write a Query for Stakeholder
1. How many users scanned each month?
SELECT USER_ID, COUNT(*)
FROM receipts
GROUP BY MONTH(DATE_SCANNED);

2. What is the name of the most expensive item purchased?
SELECT BRAND_CODE, TOTAL_FINAL_PRICE / QUANTITY_PURCHASED as price
from receipt_items
ORDER BY price DESC
LIMIT 1

## Part 3: Choose Something Noteworthy about the Data
Check the pdf file `analysis.pdf` in the repository
