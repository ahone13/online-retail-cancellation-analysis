# Online Retail Cancellation Loss Analysis

A data science and business project investigating cancellation patterns 
in a real UK-based online retailer's transaction data across two years 
(Dec 2009 – Dec 2011).

## Business Problem
Over £1.26M in cancellation losses recorded across the top 10 markets, 
with 85% concentrated in the UK alone. The goal was to identify where 
losses are coming from and what is driving them — across four analytical 
lenses.

## Structure
The analysis is divided into four sections:
- **Geography & Time** — where and when losses are concentrated
- **Customer** — which accounts drive the most loss and what their 
behaviour looks like
- **Product** — which products have the highest return rates and whether 
a Pareto pattern holds
- **Recommendations** — actionable business responses by market and 
customer segment

## My Contribution
I owned the product analysis section, including data cleaning decisions 
(StockCode M exclusion), Pareto analysis, price band segmentation, spike 
investigations, and key account product breakdowns for EIRE, Norway, 
France, and Spain.

## Tools & Libraries
Python · Pandas · Matplotlib · Jupyter Notebook

## Dataset
Online Retail II — UCI Machine Learning Repository  
UK-based online retailer | 1,048,576 transactions | Dec 2009 – Dec 2011

## Key Findings
- 438 SKUs (14.3%) account for 80% of product cancellation loss
- The highest-loss product (Ceramic Jar, £77,480) is a single bulk B2B 
event — not a quality issue
- Return rate climbs with price: 3.1% for items under £1 vs 15.7% for 
items above £50
- The only genuine recurring product signals are the Regency homeware 
line in EIRE and home décor cancellations in Spain