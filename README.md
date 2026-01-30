# AML Transaction Monitoring & Risk Intelligence Dashboard

## Project Overview
This project demonstrates an end-to-end Compliance Data Analysis workflow. I developed a risk-scoring engine and an interactive monitoring dashboard to help Compliance Officers identify potential Money Laundering (AML) red flags and fraudulent credit card activity.

## Tech Stack
* **Data Engineering:** Excel & Power Query (Data Cleaning, ETL)
* **Analytics:** DAX (Data Analysis Expressions)
* **Visualization:** Power BI
* **Domain Knowledge:** Anti-Money Laundering (AML), Merchant Category Codes (MCC), Financial Crime Detection.

## Key Features & Logic
I implemented several "Red Flag" detection rules based on industry standards:
1.  **High-Risk MCC Tracking:** Automated flagging of high-risk merchant categories (e.g., Gambling, Money Transfers).
2.  **Temporal Analysis:** Identified "After-Hours" transactions (12 AM - 5 AM) which often correlate with high-risk testing behavior.
3.  **Threshold Monitoring:** Flagged High-Value Transactions (HVT) for manual review.
4.  **Geospatial Risk Map:** Visualized transaction volume by state to identify geographic risk clusters.

## Dashboard Insights
* **Total Alerts Card:** A real-time counter of high-risk transactions.

  <img width="975" height="547" alt="image" src="https://github.com/user-attachments/assets/0a6d19dc-82ae-4e0f-aeb6-323aca17eb1a" />


* **Drill-Down Investigation Table:** Allows analysts to see specific User IDs and Merchant details for flagged alerts.

  <img width="975" height="549" alt="image" src="https://github.com/user-attachments/assets/cbdc328a-e4c3-46de-8468-e207c41a0baf" />

  
* **Risk Distribution:** Capital tied up in high-risk categories versus standard ones.

  <img width="975" height="558" alt="image" src="https://github.com/user-attachments/assets/01fd6293-7282-4fa8-86eb-8140bd461e69" />


## How to Use
1. Download the `.pbix` file.
2. Open in Power BI Desktop to explore the interactive filters.

## Data Source
https://www.kaggle.com/datasets/ealtman2019/credit-card-transactions/data
