# Nile-Bridge-Sales-Performance-Dashboard
This project was built to solve a real business problem.
Screenshot 2026-02-21 153238.png
This dashboard enables decision-makers to detect hidden losses, understand customer behavior, and take data-driven actions to improve profitability.  
 
The goal was not just to analyze data, but to **uncover hidden problems and provide actionable insights**.  

## Key Finding  
Despite achieving **254M in total sales**, the company suffers from a **49.63% return rate**, significantly impacting net sales and profitability.  

## Business Problem
The company faced high sales numbers but unclear profitability and customer complaints.

## Business Questions
- Are shipping delays causing customer complaints?
- Do higher discounts really increase sales quantity?
- What are the top cities and branches in performance and returns?
- Who are the top 10 loyal customers?

## Data Processing  

### Using Power Query:  
- Calculated shipping duration (Order Date vs Ship Date)  
- Calculated discount value  

### Using Power Pivot: 
- Built data model  
- Created key measures:
  - Total sales → 254M
  - Avg delivery time → 4.3 days (higher than expected for critical orders)
  - Net sales → ~127M
  - Return rate → 49.63% (significant business risk)
  - Total discounts → 11M+
  - Total quantity → ~44K units
 
 ## Insights  
- Return rate reached **49.63%** → major loss driver  
- Critical orders take longer than standard orders → supports customer complaints  
- Sales heavily depend on discounts → weak customer loyalty  
- Zamalek branch has highest returns despite Cairo leading sales

## Recommendations  
- Improve delivery speed for critical orders  
- Reduce dependency on discounts  
- Enhance product quality (especially Zamalek branch)  
- Build customer loyalty strategies instead of price-based competition

## Tools Used  
- Microsoft Excel  
- Power Query  
- Power Pivot 
