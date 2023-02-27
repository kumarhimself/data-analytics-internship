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

## Last Notes
Dear whomever is reading,

Hello, my name is Ayush Kumar, and I am a freshman computer science/data science major at the University of Wisconsin - Madison. I wanted to add an extra note that I am excited at the opportunity to submit my exercise for the data analytics internship. Although I have experience in Python and R for data science, I still have a long way to go, which is why working at Fetch as an intern would help me significantly in learning more as well as building up on my already existing knowledge of data science.

Thank you for reviewing my exercise!

Sincerely,

Ayush Kumar
