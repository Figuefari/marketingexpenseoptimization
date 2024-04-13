## Proyect description

We work directly from the Y.Afisha analytics department to optimize their marketing expenses.

## Tasks

1. Load the three files and optimize the data, ensuring it is of the correct type.
2. Generate reports and calculate metrics regarding: visits, sales, and marketing.
3. Write a conclusion advising marketing experts on how much money to invest and where.

## Data description

The visits table (server records with data about website visits):
- Uid: unique user identifier;
- Device: user's device;
- Start Ts: session start date and time;
- End Ts: session end date and time;
- Source Id: identifier of the advertising source the user comes from.

All dates in this table are in YYYY-MM-DD format.

The orders table (order data):
- Uid: unique user identifier placing an order;
- Buy Ts: date and time of the order;
- Revenue: revenue from Y.Afisha for this order.

The costs table (marketing expenses data):
- source_id: advertising source identifier
- dt: date;
- costs: expenses on this advertising source on this day.

## Table of contents

1. Initialization:
   
   - Verification and Description
   - Data Loading
   - Preliminary Conclusions
   
2. Data Preprocessing:
   
   - Data Correction
   - Checking for Missing Data
   - Duplicate Records
   - Data Validation
   - Preprocessing Conclusions
   
3. Data Analysis:
   
   - Question Formulation
   - Product Analysis
   - Sales Analysis
   - Expense Analysis
   - Gross Profit
   - Acquisition Cost
   - Return on Investment
   - Conclusions
   
4. Final Conclusions:
   
   - Analysis Summary
   - Observations
   - Recommendations

## Used libraries

- pandas 
- matplotlib
- scipy
- numpy
- seaborn
