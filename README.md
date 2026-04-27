# Excel_Project
This project is a high-performance Excel-based financial management tool designed to process and visualize over 1,000 transaction entries. It demonstrates the transition from raw data entry to automated business intelligence, providing users with real-time insights into spending habits, budget adherence, and financial health.
## Technical Skills Used
The following advanced Excel functionalities were implemented to ensure scalability and accuracy:

* **Data Aggregation:** Utilized `SUMIFS` and `INDEX/MATCH` logic to link transactional data with categorical budgets.
* **Data Integrity:** Implemented **Data Validation** (drop-down menus) to ensure consistent data entry across sheets.
* **Business Intelligence:** Built dynamic **Pivot Tables** to summarize n number of rows of data instantly.
* **Interactivity:** Integrated **Slicers** and **Timelines** for a "software-like" user experience.
* **Visual Feedback:** Applied **Conditional Formatting** for automated budget status alerts (e.g., Healthy vs. Over Budget).
* **Clean UI/UX:** Removed gridlines and protected worksheet structures to mimic a standalone application interface.

## Dataset Specification
* **Volume:** 1,000+ rows of synthetically generated financial data.
* **Timeframe:** Full calendar year (2026).
* **Columns:** Includes Date, Transaction Description, Category (Rent, Groceries, Transport, etc.), and Amount.
* **Generation Method:** Data was generated using logical Excel functions (`RANDBETWEEN`, `DATE`, `INDEX`) to simulate realistic market spending patterns.

## How to Use
1.  **Overview:** Open the `Dashboard` sheet to see the high-level financial summary.
2.  **Filter Data:** Use the **Timeline Slicer** on the right side of the dashboard to filter all charts and tables by specific months or quarters.
3.  **Analyze Trends:** View the "Category vs. Budget" chart to identify high-spending areas.
4.  **Manage Budget:** Navigate to the `Setup` sheet to adjust monthly limits. The dashboard and status indicators will update automatically.
5.  **Add Data:** Enter new transactions in the `Transactions` sheet. Simply right-click the Pivot Table on the dashboard and select **'Refresh'** to include new entries in the analysis.

## Project Structure
* `Dashboard`: Interactive visual reporting layer.
* `Setup`: Budget definitions and categorical logic.
* `Transactions`: Raw data repository (1,000 entries).

---
*Developed as part of a Data Analytics Portfolio to demonstrate Excel proficiency and data management capabilities.*
