# GODWIN-ABEM-S-ANALYZED-DATA
<img width="219" height="254" alt="image" src="https://github.com/user-attachments/assets/35ca68c6-e06b-4d99-99a0-212c0c0a1dde" />


## Description:
## The excel work on Authentic Electronics Ltd Sales Analysis. It aims to analyze Authentic Electronics Ltd products and customer review data to generate insight that can guide product improvement, customer, and potential revenue. key features are: Clean Dashboard, pivot tables, and visual charts to support business decision making.
## Data Content
### Rows: were 101 in Total.
 ### Columns: were 9 in Total.
## Tool Used:
Microsoft Excel (Excel functions, Pivot Tables & charts).
## Data Cleaning Actions
Some data cleaning steps were applied to make the dataset proper for analysis without errors.
## Steps:
### Product Name Column: cleaned using Proper & Left function (nesting), removing extra spacing in names.
### Category Column: cleaned using Left and Find function. The delimiter used was “|”.
### Helper columns: calculated columns and category columns were used in generating the Dashboard.
## Key Business Questions Answered
1.	Which region has the highest customers?
Rows: Region
Values: Customer → count
2.	Which product was sold the highest?
Rows: product
Values: unit sold → sum
3.	Which category sold the highest?
Rows: Category
Values: unit sold → Sum
4.	Which customer paid the highest unit price?
Rows: customer
Values: unit price→ Sum
5.	How many units were sold by the unit price?
Rows: unit sold
Values: unit price→ Sum
6.	Which product has the highest unit price?
Rows: product
Values: unit price→ Sum
7.	Which date recorded the highest unit sales?
Rows: date
Values: unit price→ Sum
8.	Which sales rep has the highest total revenue?
Add calculated column:
=unit price * unit sold
Rows: sales rep
Values:  Total revenue→ Sum
9.	Which region has the highest sales reps?
Rows: Region
Values:  Sales rep → Sum
## Section Details
### Column Names: Date, Region, Product, Category, Unit sold, Unit price, Revenue, Sales rep, Customer.
### Excel formulas used: PROPER() TRIM() FILTER()
## cleaned data
<img width="975" height="462" alt="image" src="https://github.com/user-attachments/assets/4bfa1378-bbf1-4857-8112-75fb2b62fbf8" />
## Analytics Dashboard
<img width="975" height="484" alt="image" src="https://github.com/user-attachments/assets/32773832-92f5-4d07-8a9e-782b24192a76" />
      
   ## Findings
1.	East has the highest customers of 34 out of 100 customers across the major four regions. While the region with lowest customer is the North with 18 customers
2.	Tablet T8 has the highest unit sold product of 226. While the lowest unit sold product is unknown product with 10 unit sold
3.	The product with the highest unit price is Laptop A15 with unit price of ₦ 10,025,000.00. while the product with the lowest unit price is unknown product with unit price     of ₦65,000
4.	The customer that paid the highest price is Omega wholesales with ₦6,018,500.00, the customer with the list amount paid is Adewales Tores with ₦415,000.00

  	## Conclusion
Using Excel to generate business ready insight from identifying, understanding and knowing pricing impacts that affect revenue, when explored correctly.
      
   ## RECOMMENDATIONS
The following recommendations were made based on my findings
1.	Since the East has the highest customers, the region should be periodized by establishing more branches within the region
2.	The company should focus on Tablet T8 majorly because of the highest demand among other products
3.	Omega wholesales paid the highest price; hence he should be considered the most valuable customer with fringe benefits for motivation
