# Newborn Screening Dashboard

## Project Background
The Newborn Screening (NBS) dashboard presents data on blood spot and critical congenital heart disease (CCHD) screening performance metrics found in the NBS quarterly reports. It displays data by NBS submitter code and includes data from the last four quarters. The NBS Program aims for the dashboard to be utilized to enhance the NBS process within hospitals. By meeting these metrics, hospitals can ensure that all infants have the opportunity to have blood spot and CCHD screening completed as effectively as possible.


### Key Metrics

**Bloodspot Screening**
- Unsatisfactory Screening: specimen quality is poor for analysis.
- Card Errors: inaccurate information on specimen submission
- Receipt by Appropriate Date: specimen transfer to lab timeliness
- NBS Card Number: identification number present or not
- Late Screens: specimen collected after a certain amount of time
- Biotrust form: associated form is present and completed

**Critical Congenital Heart Disease (CCHD)**
- Reported Screens: Total Hospital Screens/Total Michigan Screens
- Reported on Time: Total Hospital Screens Reported on Time/Total Michigan Screens Reported on Time
- Timely Screens After Birth: Total Hospital Screens within Optimal TimeFrame/Total Michigan Screens Reported on Time within Optimal TimeFrame

### Dashboard Purpose
The dashboard was created so providers could see how they compare against all state hospitals with the intention of encouraging quality improvement efforts based on whether they met the target for each metric.

## Summary of Project Overall

I met with the data owners and subject matter experts to determine what the purpose of the dashboard was. During these meetings, we also determined what information the audience would like to see and what information would be most beneficial in helping healthcare staff target key problem areas. After this was determined, there were two stages of product design. Stage one resulted in the initial design of the dashboard layout, separation of data/metrics, and general theme. Stage two included refining the design, adding more clarity to target metric definitions, and creating documentation to ensure the smooth transition of the product into the customer's staff who would manage it.

### Documentation: Highlighting Main Sections
* Transforming/Updating the data using a pre-designed query in Power BI
* Refreshing the data
* Publishing the dashboard to Power BI Service

## Data and Schema
![The data model behind the newborn screening dashboard.](https://github.com/Kajones21/PowerBI-NBS-Dashboard-Project/blob/main/PBI_DataStructure_NBS.png
"Newborn Screening Data Model")

### Validation Checks
* No duplicate submitter code
* Ensured each column type was assigned based on necessary analysis
* Data range only encompassed the past 4 quarters

## Dashboard Screenshots

### Bloodspot Screening Pages
![Newborn Screening Bloodspot Metric 1](https://github.com/Kajones21/PowerBI-NBS-Dashboard-Project/blob/main/NBS_Blood_s1.png)
![Newborn Screening Bloodspot Metric 2](https://github.com/Kajones21/PowerBI-NBS-Dashboard-Project/blob/main/NBS_Blood_s2.png)
![Newborn Screening Bloodspot Metric 3](https://github.com/Kajones21/PowerBI-NBS-Dashboard-Project/blob/main/NBS_Blood_s3.png)
![Newborn Screening Bloodspot Metric 4](https://github.com/Kajones21/PowerBI-NBS-Dashboard-Project/blob/main/NBS_Blood_s4.png)
![Newborn Screening Bloodspot Metric 5](https://github.com/Kajones21/PowerBI-NBS-Dashboard-Project/blob/main/NBS_Blood_s5.png)
![Newborn Screening Bloodspot Metric 6](https://github.com/Kajones21/PowerBI-NBS-Dashboard-Project/blob/main/NBS_Blood_s6.png)

### Critical Congenital Heart Disease

![Newborn Screening CCHD Metric 1](https://github.com/Kajones21/PowerBI-NBS-Dashboard-Project/blob/main/NBS_Blood_c1.png)
![Newborn Screening CCHD Metric 2](https://github.com/Kajones21/PowerBI-NBS-Dashboard-Project/blob/main/NBS_Blood_c2.png)
![Newborn Screening CCHD Metric 3](https://github.com/Kajones21/PowerBI-NBS-Dashboard-Project/blob/main/NBS_Blood_c3.png)

### Contact Page

![Newborn Screening Contact Page](https://github.com/Kajones21/PowerBI-NBS-Dashboard-Project/blob/main/NBS_Blood_contact.png)

## Technologies Used

* Excel file
* Power BI
