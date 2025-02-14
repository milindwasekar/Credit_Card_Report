# Credit Card Financial Weekly Dashboard Report

## Objective: 
---
This dashboard gives real-time insights into key credit card metrics, helping stakeholders make informed decisions.
It is designed to provide real-time insights into critical performance metrics and trends in credit card operations. 
This dashboard empowers stakeholders to monitor and analize data effectively for informed decision-making.

## Data Source:
Uses SQL to fetch data automatically from the database, ensuring up-to-date information.

## Data Processing: 
Utilizes DAX for calculating weekly metrics and trends, providing a complete view of credit card performance.

```DAX
Total Sales = CALCULATE(
SUM('sales'[dataset]
```

## Dashboard Features:

### Sankey Chart : 
Preparing the data for Showing  Flow of Data from Card Category to Card Type and utilise this data to build a Visual called Sankey Chart.
![sankey](https://github.com/user-attachments/assets/d1fbb2d2-bac4-459e-87eb-933f9565aee0)


### Transaction Report: 
Shows revenue and trends by income, marital status, dependents, education, and weekly updates.

![transc](https://github.com/user-attachments/assets/d7d29133-e8ff-4024-a70e-2458381a1e5a)


### Customer Report:
Analyses revenue by gender, job role, education, spending type, acquisition cost, quarterly revenue, and total transactions.

![Cust](https://github.com/user-attachments/assets/c491036a-e835-465b-8755-14970d2ba5f1)

Interactive Visualization: User-friendly with interactive buttons and dynamic graphs for deeper data exploration.
