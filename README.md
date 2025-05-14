# Car Sales Analysis
---

# Table of Content

[Project Overview](#project-overview)

[Data Sources](#data-sources)

[Tools Used](#tools-used)

[Data Preparation](#data-preparation)

[Data Overview](#data-overview) 

[Tabular Overview](#tabular-overview) 

[Analysis Visualisation](#analysis-visualisation)

[Exploratory Data Analysis](#exploratory-data-analysis)

[Key Findings](#key-findings)

[Recommendations](#recommendations)

---

## Project Overview

This Project assesses car sales data of the United State of America to provide insights on sales performance by various attributes such as car colour, region, gender and body style. Using pivot table, i examined data points like total sales by colour and region, transmission, by body style and gender, by gender and transmission, and average sales by body style. This analysis helps to understand key factors drivinng car sales in the USA and identifies patterns across different segments.

## Data Sources

The primary dataset used for this analysis is a Research site "Kaggle.com" and contains datasets on Car Sales Transactions.

## Tools Used

1. Excel
- Data cleaning and structuring.
  - [View RawData here](https://ibb.co/M58p5ZCP)
  - [View CleansedData here](https://ibb.co/NnSmpnYw)
- Exploring and Analyzing trends in car sales. 
- Data Visualization
  - [View Visuals Here](https://ibb.co/TBY5H8gV)

2.	PowerBI 
  - Data ingestion: Data is get as an excel file
	- For data transformation/manipulation. [View here](https://ibb.co/G44FTRVN)
	- For Dashoard Creation. [Visual here](https://ibb.co/Tx3xxd8M) 
	- For visuals that present data insights in a user-friendly format. 


## Data Preparation

In the initial data pre-processing phase, the following tasks were performed:

  i.	Data loading and inspection.
  
  ii.	Data cleaning and formatting.

## Data Overview 

The dataset includes the following columns:

- 	CarID  : Unique identifier for each car sold.
- 	SaleDate: Date when the sale was completed.
-  CustomerName: Names of the purchasers of vehicle 
-  Gender Gender of the buyer 
-  Income: Income of the buyer
-  DealerName: Authorized seller from whom car is being sold
-  Company: Different company that manufactures car models
-  Model: Version of manufactured cars 
-  Engine: Type of engine
-  Transmission Automatic or Manual 
-  Color: Color of car
-  Price:The amount of Car model
-  BodyStyle: The shape, design and structure of car's exterior 
-  Region: Geographic location where the car was sold.

## Tabular Overview 

A brief overview of the tabular datasets to be analyzed. The first 5 Colums are displayed below. 

Car ID|Date|	Customer| Name|	Gender|	Annual Income|	Dealer_Name|	Company|	Model|	Engine|	Transmission|	Color	Price|	Dealer_No| 	Body Style|	Phone|	Dealer_Region|
|-----|----|-----|-----|-----|----|-----|-----|-----|----|-----|-----|-----|----|-----|-----|
C_CND_000001|1/2/2022|	Geraldine|	Male|	13500|	Buddy Storbeck's Diesel Service Inc|	Ford|	Expedition|	DoubleÃ‚Â Overhead Camshaft|	Auto|	Black|	26000|	06457-3834|	SUV|	8264678|	Middletown|
C_CND_000002|1/2/2022|	Gia|	Male|	1480000|	C & M Motors Inc|	Dodge|	Durango|	DoubleÃ‚Â Overhead Camshaft|	Auto|	Black|	19000|	60504-7114|	SUV|	6848189|	Aurora|
C_CND_000003|1/2/2022|	Gianna|	Male|	1035000|	Capitol KIA|	Cadillac|	Eldorado|	Overhead Camshaft|	Manual|	Red|	31500|	38701-8047|	Passenger|	7298798|	Greenville|
C_CND_000004|1/2/2022|	Giselle|	Male|	13500|	Chrysler of Tri-Cities|	Toyota|	Celica|	Overhead Camshaft|	Manual|	Pale White|	14000|	99301-3882|	SUV|	6257557|	Pasco|
C_CND_000005|1/2/2022|	Grace|	Male|	1465000|	Chrysler Plymouth|	Acura|	TL|	DoubleÃ‚Â Overhead Camshaft|	Auto|	Red|	24500|	53546-9427|	Hatchback|	7081483|	Janesville|


## Analysis Visualisation
Chart Visualisation of the pre-proessed car sales data;

![Screenshot (40)](https://github.com/user-attachments/assets/34304c3e-d9e2-4148-9019-8a35485b5970)


![Screenshot (38)](https://github.com/user-attachments/assets/a650c18d-88cd-47e7-bfda-1470f6c60c56)




## Exploratory Data Analysis

EDA involved exploring the sales data to answer key questions, such as:

  i.	Which color are each genders more likely to purchase . What car color relates to the likelihood of purchase from each gender. 
  
  ii.	The comparison rate of purchase of transmission types 
  
  iii.	How this transmission type affects sales among genders.
  
  iv.	Which geographical location has the highest and lowest sales.  

  v.	What is the popularity of each body style among customers.

  vi. What is the monthly performance trend in revenue. 

## Key Findings
The analysis results are summarized as follows:

1.	Revenue by color indicates the pale white outperforming the black and red cars significantly
	
2.	The region *AUSTIN* has the highest performing sales and lowest sales being *MIDDLETOWN*
	
3.	53% of sales comes from auto transmission cars compared to 47% for manual. The Auto cars brings in grerater sales than that of the manual across all Dealer Region
	
4.	Male buyers are about 3 times more than female buyers
	
5.	 A gradual increase in average sales of body sales inorder ascending; SUV to Hatchback to Passenger to Hardtop to Sedan
	 
6. SUVs has the lowest average sales price(26, 768) but the highest volume sold(5,039 units for males and 1,335 for females). SUVs and Hatchbacks brings in solid revenue across all region
 	
7.	The month of December and November clearly has the largest revenue of ~100M and ~97M respectively surpassing other months while January(22M) and February(21M) sales being the smallest
	
8.	The Revenue of car design to every geographical area is well differentiated to understand the best category of style for every region

9.	
    

## Recommendations

### Transmission

- Prioritize inventory toward Auto Models.
- Educate customers about the ease and comfort of Auto, especially targeting younger and first-time buyers.
- Offer driving workshops and trade-in offers for Manual car owners to upgrade, to reduce or avoid overstocks. 
- Target marketing of manual cars more unto commercial use and budget-conscious buyers

### Body Stlye

 - Upgrades and Upsell SUVs
- Introduce mid-range or luxury SUVs to raise the average sale price.
- Body styles of Sedan, Hardtop and Passenger cars should be made more attractive -Customization
- Model features should be highlighted to strategically target customers
 
### Colors

 - Stock more vehicles in pale white and black
 - Implement data driven discount strategies for Red-colored models to optimize inventory balance and reduce holding costs.
 - Consider introducing light shades of car colors since pale white is successful.

### Genders

 -Design models with female drivers in mind and safety-focused advertisements. 
 - More marketing programs should be targeted towards male preferences (e.g power, performance, durability)

### Region

- Expand Dealership Presence, Advertisement and Resources in Austin, Janesville and Scottsdale – Showroom expansions. 
- Reassess Middletown, Pasco, Greenville- Wrong car models?, High Pricing?, Poor Customer Service?. Introduce better-trained sales teams and offer location based promos.

### MONTHLY Trend

- Increase ad spends in Q4
- Plan inventory to meet the surge: Stock SUVs, Hatchbacks, Pale White and Black AUTO Cars ahead of time.


  💻 📊







  
