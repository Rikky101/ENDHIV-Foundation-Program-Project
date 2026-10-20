# ENDHIV Foundation Program Project
## Overview
The EndHIV Foundation HIV Program Dashboard is a healthcare data analytics project based on a simulated scenario involving EndHIV Foundation. This Nigerian non-governmental organization provides HIV treatment and care services across six healthcare facilities in Lagos and Abuja.
The project addresses a common operational challenge: managing program information across multiple Excel files. These processes can be time-consuming, increase the risk of reporting errors, and delay access to actionable information. Using Microsoft Power BI, I developed an interactive dashboard that brings together patient records, viral load testing, facility information, pharmacy stock data, and program targets to provide a consolidated view of program performance. The dashboard is designed to help stakeholders monitor key performance indicators, identify operational gaps, and make more informed decisions about patient follow-up, treatment outcomes, and medicine availability.


## Project Scope
The dashboard focuses on two main areas:
1. Program Overview
This section provides a high-level view of HIV program performance through KPI cards, charts, trends, and interactive filters.
It covers: Active patient count, Total viral load tests, Patient retention rate, Viral suppression rate, New patient initiations, Treatment status distribution, Patient demographics by age group and gender, Regimen distribution by gender, and Viral suppression trends over time.
2. Operational Performance
This section focuses on patient follow-up, facility performance, and pharmacy operations.
It includes: Kept and missed appointments, Follow-up calls and patient returns after follow-up, Facility-level viral suppression and ART initiation rates, Stockout days by antiretroviral regimen, Current stock levels, and Medicine dispensing trends over time.

Interactive filters enable users to explore the dashboard by facility, date, and age group.

## Business Objective: 
The primary objective was to transform fragmented healthcare program data into a consolidated and interactive reporting solution. Specifically, the project aimed to:
1.  Monitor key HIV program indicators, including active patients, viral load tests, patient retention, and viral suppression.
2.  Compare facility-level performance using viral suppression and ART initiation rates.
3.	Track missed appointments, follow-up calls, and patient returns following follow-up.
4.	Monitor medicine stock levels, stockout days, and dispensing trends across antiretroviral regimens.
5.	Improve the accessibility and interpretation of program performance information through interactive visualizations.
By leveraging data analytics, the project seeks to transform raw membership data into actionable insights that support MyGym’s long-term growth, competitiveness, and member-centric innovation.

## Document Purpose: 
This documentation summarizes the key insights derived from the ENDHIV Foundation project. This documentation serves as a guide for project stakeholders, providing insights into the project's objectives, data sources, data analysis, and any other relevant information.

## Use case:
The dashboard is designed for stakeholders who need a consolidated view of HIV programme performance in the simulated scenario. Potential users and uses include :
1.  Program coordinators and management: Review key performance indicators and monitor program performance across facilities.
2.  Facility teams: Compare facility-level indicators and identify areas that may warrant further review.
3. Patient follow-up teams: Monitor missed appointments, follow-up calls, and recorded returns after follow-up.
4. Pharmacy and supply teams: Review stock levels, stockout days, and dispensing trends by regimen.
5. Monitoring and reporting teams: Use the dashboard to explore trends and prepare program performance discussions.
   
## Skills Demonstrated:
●	Data cleaning and preparation

● Data modelling and relationships

●	KPI development and performance monitoring

●	Time Intelligence

●	Data visualization and Interactive dashboard design

●	Communication of data-driven insights

## Data Source:
[Patients](https://github.com/Rikky101/ENDHIV-Foundation-Program-Project/blob/main/patients.csv): This contains 19 columns and 400 rows of patient information and treatment-related records, including patient name, gender, age group, last appointment date, drug regimen, and so on.

[Viral Load Tests](https://github.com/Rikky101/ENDHIV-Foundation-Program-Project/blob/main/viral_load_tests.csv): This contains 9 columns and 737 rows of viral load testing and suppression monitoring, including the reason behind tests, test month, and whether suppression was achieved or not. 

[Facilities](https://github.com/Rikky101/ENDHIV-Foundation-Program-Project/blob/main/facilities.csv): This contains 5 columns and 6 rows of facility information and facility-level reporting, including facility name, state, and local government area in which the facility operates.

[Pharmacy Stock](https://github.com/Rikky101/ENDHIV-Foundation-Program-Project/blob/main/pharmacy_stock.csv): This contains 9 columns and 216 rows of the drug regimen stock level, stockout information, and pharmacy operations, including opening stock, closing stock, dispensed tablets, and the year in which the pharmacy stock was recorded.

[Targets](https://github.com/Rikky101/ENDHIV-Foundation-Program-Project/blob/main/targets.csv): This contains 5 columns and 6 rows of program performance targets, including viral suppression rate target and ART initiation target.

## Data Analysis: 
Two key transformation steps were carried out in Power BI:
1. Calendar table creation: A dedicated calendar table was created to support date-based analysis and time-related filtering in the dashboard.
   
2. Table relationships: Relationships were established between the relevant tables to connect the datasets and support analysis across patient, viral load testing, facility, pharmacy/stock, and target information.
These steps support consistent date filtering and allow visuals to draw on related information across the model.

## Data Analysis and Visualization:
Dynamic visuals, including column charts, donut charts, and comparative bar charts, were used to create a dashboard to answer the business objectives and convey information intuitively. The dashboard highlighted several areas that may require further investigation and operational attention. The accompanying demo video walks through the dashboard's main features, explains the purpose of each section, highlights key findings, and demonstrates the data-refresh workflow.

1. Viral Suppression and Patient Retention:
The dashboard reported a viral suppression rate of 73% and a patient retention rate of 78%.
These indicators provide a high-level view of program performance and can help stakeholders identify areas for closer review. Further investigation against the program's applicable targets and facility-level results would help establish where improvement efforts should be prioritised.
2. Antiretroviral Stock Availability:
The dashboard recorded 52 stockout days for TLD, while the other regimens displayed in the stock summary recorded zero stockout days. This finding highlights the importance of monitoring stock availability and investigating potential supply-chain or inventory management gaps that could affect service continuity.
3. Missed Appointments and Patient Follow-up:
The dashboard recorded: 103 missed appointments, 77 follow-up calls made,51 patients recorded as having returned after follow-up
4. Differences in Facility Performance:
The facility performance table enables comparison of viral suppression and ART initiation rates across participating facilities. All facilities were behind on their viral suppression rate target, but met their ART initiation rate target. 
This allows program teams to identify facilities that may need additional investigation, targeted support, or further review of their service delivery processes. 

Dashboard: [Click here to interact with the dashboard](https://github.com/Rikky101/ENDHIV-Foundation-Program-Project/blob/main/YHPT%20HIV.pbix) 

Project demonstration: [Click here to view the demovideo](https://github.com/Rikky101/ENDHIV-Foundation-Program-Project/blob/main/ENDHIV%20Foundation%20Project%20Demovideo.mp4)

## Recommendation:
Based on the dashboard findings, the following actions could be considered within the simulated program scenario:
1. Investigate the factors contributing to the reported TLD stockout days and strengthen stock monitoring and replenishment processes.
2. Review facility-level viral suppression results against the applicable program targets.
3. Examine missed appointment patterns and strengthen follow-up processes for patients who miss scheduled visits and failed to return after a follow-up call.
4. Monitor the outcomes of follow-up activities to understand patient re-engagement patterns.
5. Use the dispensing and stock dashboards to support inventory planning and improve visibility into medicine availability.
   
## Conclusion:
This project provided an opportunity to apply data analytics to a healthcare program scenario, translating multiple datasets into a consolidated view of program performance. Beyond visualisation, the project involved thinking about how different data sources relate to one another, which indicators matter to program stakeholders, and how information can be presented to make potential operational gaps easier to identify.

Thank You for Reading!

Contact me: balogunaryke@gmail.com 

