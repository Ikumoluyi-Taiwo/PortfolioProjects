 # Forggith_Analysis

## About The Project.
Forggith Pharmaceuticals (Forggith) is an imaginary Pharmaceutical Manufacturing company based in Germany that produces medical drugs which get to their consumers through their Distributors. A template was provided for their distributors to capture records of their sales which are then sent to Forggith on a monthly basis. This data is then used for reporting and analysis by Forggith to achieve their goals Sales and Marketing objectives through tracking and monitoring of KPIs. In their efforts to maximise growth, Forggith works with a team of Sales and Marketing pros who ensure retailers are able to get their products through the distributors. That is, Forggith does not sell directly to retailers or end-users, they sell to Distributors. But they maintain interaction with retailers, through their Sales and Marketing pros.

## Project Requirement.
Forggith is looking to create some Power BI Reports to assist in guiding their strategies, tactics and operations as a company. For a start, they have identified a couple of numbers they will like to report from their data as reports.

## Datasets. 
There are two raw Excel files named **PharmTargets** and **PharmDataset** provided by FORESIGHT BI & ANALYTICS.

## Skills Shown.
The datasets needed little cleaning but most of the challenges lay in the transformation process.

## Transformation and Data Modelling.
The Target Tables contain information/records of Yearly/Monthly Product Targets (Volume) assigned to each Sales representative, identified by the SalesRepID. This table was duplicated four times for each distinct year (e.g., 2022, 2023, 2024, and 2025) separately. Subsequently, the corresponding tables were appended to form a new table, consolidating the previously separate yearly Target columns. The columns were edited and renamed based on the information they contain.
The Target Table was then merged with the DimProducts Table using the Primary/Foreign Key relationship of the ProductID column in both tables to retrieve the Product Price. This is important in order to calculate the budgeted Target Revenue. The Month and Year columns were duplicated, and the duplicated columns were then merged to form a Date column. Furthermore, the Sales 2022 and Sales 2023-2025 tables were appended to create a new Sales Table that has all Sales records from years 2022 to 2025 which was then merged with the DimProducts Table using the Primary/Foreign key relationship of the ProductID Column in both Tables to get the Product Price.This is crucial in order to calculate the Actual Revenue.

## Model.
![Data Model](https://github.com/Ikumoluyi-Taiwo/PortfolioProjects/assets/139241043/652cdd03-141c-4cd8-bef9-3f9c80ef7579)

## Analysis.
1. The Sales Representative can track their performances through-out the periods to plan their marketing activities.
2. The Team Managers can track their teams' performances through-out the periods to plan their teams' activities.
3. Executive team can track Revenue numbers to monitor alignment with the set targets to influence medium to long term strategies.

## Sales Performance Overview.
1. Total  Revenue
2. Total Revenue Year To Date (YTD)
3. Total Revenue Previous Year YTD
4. Total Revenue Same Period Last Year(SPLY)
5. Total Target
6. Total TargetYTD
7. Actual Revenue Performance Previous Year YTD vs Target Previous Year YTD
8. Actual Revenue Performance YTD vs Target YTD
9. Revenue Month on Month Percentage Change
10. Revenue Distribution by Location
11. Revenue by Channel
12. Revenue by Product Class

![Sales Report 1](https://github.com/Ikumoluyi-Taiwo/PortfolioProjects/assets/139241043/bb5c4cea-ef6e-4d0f-9d2c-a59b76e4d3f1)
![Sales Report 2](https://github.com/Ikumoluyi-Taiwo/PortfolioProjects/assets/139241043/ffe6775b-0fa2-4568-8ce1-73aaf3132432)

## Marketing Performance.
1. Revenue Achieved vs Revenue Target
2. Volume Achieved vs Volume Target
3. Actual Revenue by Sales Representative
4. Target Revenue Achievement% by Sales Representative
5. Actual Volume by Sales Representative
6. Target Volume Achievement by Sales Representative
7. Actual Revenue Achievement by Sales Team
8. Revenue and Volume Achievement by Product.

![Marketing Performance 1](https://github.com/Ikumoluyi-Taiwo/PortfolioProjects/assets/139241043/418b3eab-5631-4bb8-a50e-241e351b45d7)
![Marketing Performance 2](https://github.com/Ikumoluyi-Taiwo/PortfolioProjects/assets/139241043/33e462b0-8480-4062-9524-8a522dce951e)

## Report.
You can find the full report of this Analysis here: https://app.powerbi.com/reportEmbed?reportId=73496be3-742d-4bc4-b8dd-6f60f7f80607&autoAuth=true&ctid=c1b84f64-1fcc-4038-a4fa-2bfdda89f208

## Conclusion.
The request from the stakeholders was fulfilled, and a report addressing their demands produced. 






