# Healthcare Data Analysis
## Overview
This Power BI project aims to create an interactive dashboard for analyzing the healthcare data across 151 hospitals. It helps users gain insights into efficiency by focusing on cost metrics and length of stay (LOS). The project focuses on providing a user-friendly interface for visualizing trends and understanding the key factors influencing them. 

## Data Preprocessing
DAX was used to add the measures such as:
- Percentage Variance for Average Cost
- Percentage Variance for Average Length of Stay
- Average Cost per Discharge
- Average Length of Stay
  

These measures were used to assess how much better or worse a service area or hospital was performing compared to others.

The table Surgical Program Volume Summary was calculated using DAX and includes the number of discharges and total surgeons per facility.

## Reports and Visualisations
### Length of Stay (LOS) Comparison
This report displays the top 15 hospitals and their average length of stay and total discharges. It also features the top 3 best performing hospitals in terms of average length of stay, and the bottom. The key insights are used to show that the leading cause of an increased length of stay is the mortality risk of the illness.

### Cost per Discharge Comparison
This report displays the top 15 hospitals and their average cost per discharge and total discharges. It also features the top 3 best-performing hospitals in terms of average cost per discharge, as well as the bottom. The key insights are used to show that the leading causes of an increased length of stay are the mortality risk and severity of the illness.

### Hospital Profile
This report visualizes the number of discharges based on severity of the illness, risk of mortality, patient disposition, and diagnosis. Interacting with these graphs allows the user to see which hospitals have more severe cases, and this is reflected in them having a longer length of stay. It can also be used to view which diagnoses require a longer length of stay and cost more.

## Possible Data Driven Decisions
- Relocate surgeons to hospitals that perform surgeries in their specialty more frequently.
- Open another hospital or expand existing ones in New York because they have a higher Average Length of Stay and Cost per Discharge.

## Future Work 
- Assess patient, hospital, and surgeon density
- Highlight the most expensive procedures
- Compare LOS by procedure across hospitals

## Installation and Setup
1. Clone the repository
2. Open Power BI: Launch Power BI Desktop.
3. Open Project File: Open the .pbip file in Power BI Desktop.
