# Insurance-DashBoard-
Its a  interactive Insurance Analytics Dashboard Developed Using the  Power BI, using SQL Server as the data source. All data cleaning, modeling, DAX measures, and visualizations were done directly in Power BI. The dashboard provides a clear view of premium revenue, claim amounts, policy activity, demographics, and claim status trends.

📌 Project Overview
This project delivers a comprehensive analysis of insurance policies and claims using Power BI Desktop.
The raw CSV was imported into SQL Server purely for storage, and then connected to Power BI.
All data cleaning, transformations, relationships, DAX calculations, and visual design were handled inside Power BI.
The dashboard is designed to help insurance teams understand claim behavior, policy performance, customer trends, and financial exposure.

📌 Tech Stack
SQL Server (Data Source Only)
Power BI Desktop (Data cleaning, modeling, analytics, DAX, visuals)
CSV Dataset

📌 Key Features & Insights in the Dashboard
1. Core KPI
Premium Amount: 5.98M
Coverage Amount: 600.55M
Claim Amount: 16.91M
Gender Split: ~5001 Female | ~5003 Male
→ Near equal distribution simplifies demographic comparison.

2. Premium Amount by Policy Type
Travel: 2.5M (highest)
Health: 1.2M
Auto: 1.0M
Life: 0.7M
Home: 0.6M
→ Travel policies are the major revenue generator in the dataset.

3. Policy Activity (Active vs Inactive)
Active Policies: 5.82K (58%)
Inactive Policies: 4.19K (42%)
→ Customer retention is an issue — many policies drop off.

4. Claim Status Overview
Rejected: 4.4K (highest)
Settled: 3.4K
Pending: 2.3K
→ High rejection rate signals documentation issues or strict process.

5. Claim Amount by Age Group
Adults: 8.8M
Elders: 6.4M
Young Adults: 1.7M
→ Adults form the largest claim risk segment.

7. Policy Type vs Claim Distribution
For each policy type (Auto, Health, Home, Life, Travel), the dashboard breaks down:
Pending claim amount
Settled claim amount
Rejected claim amount
Useful for identifying which product categories are performing well or bleeding losses.
