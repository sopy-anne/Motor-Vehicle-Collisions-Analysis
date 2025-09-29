# Motor-Vehicle-Collisions-Analysis
![](https://github.com/sopy-anne/Motor-Vehicle-Collisions-Analysis/blob/main/download%20(2).jpg)

## Introduction 

Every time a careless driver takes the road, the risk of a collision rises—often resulting in injury or even death. 
This capstone project analyzes the New York City Police Department's records of motor vehicle collisions between January 2021 and April 2023, capturing over 238,000 incidents. 

The dataset includes details such as borough, street name, date and time of incident, contributing factors, vehicle type, and the number of persons, motorists, cyclists, and pedestrians injured or killed. 

This analysis provides insights into the total number of accidents, deaths, and injuries, as well as the frequency of collisions by time of day, monthly accident trends, streets with the highest accident rates, vehicles most responsible for collisions, and the key factors contributing to accidents and fatalities.

### Key Research Questions;
1. Are there any seasonal patterns when the % of total accidents is compared by month?
2. What is the accident frequency by day of week and hour of day? Based on this data, when do accidents occur most frequently? 
3. On which particular street were the most accidents reported? What does that represent as a % of all reported accidents? 
4. What was the most common contributing factor for the accidents reported in this sample (based on Vehicle 1)? What about fatal accidents specifically? 


## Data Preparation & Analysis

- The dataset was cleaned and transformed using Power Query Editor, where custom columns were created to extract year, month, day, and hour from the collision date. 
- Spelling errors were corrected and missing values replaced. 
- DAX functions were applied to calculate accident counts and percentages of injuries and deaths.

### Visualization and Dashboard

The Visualizations used included:

- Clustered column charts for frequency of accidents by time of day and day of the week.
- Line charts for monthly and yearly trends of accidents and fatalities.
- Stacked column charts for vehicle type contributions to accidents and deaths.
- Clustered bar charts for accident percentages across streets.
- Pie charts for the share of persons, motorists, cyclists, and pedestrians killed.
- Matrix visualization for the contribution of each factor to total accidents and deaths.

The dashboard for a summarized insight:
![](https://github.com/sopy-anne/Motor-Vehicle-Collisions-Analysis/blob/main/Screenshot%202025-09-29%20012923.png)
![](https://github.com/sopy-anne/Motor-Vehicle-Collisions-Analysis/blob/main/Screenshot%202025-09-29%20012947.png)

## Key Insights

- The analysis shows that accidents are most frequent between 2–6 PM daily, at 8 AM on weekdays, and around midnight on weekends. 
- Monthly trends reveal that January, February, and March consistently recorded the lowest accident counts, while other months had higher records, except for April 2023, which had incomplete data. 
- Passenger vehicles were the most common cause of accidents, accounting for 82% of incidents and 65% of deaths, while emergency services, limousines, and fire service vehicles recorded the lowest rates. 
- Belt Parkway emerged as the most dangerous location, with 6% of all accidents—3% higher than the next street—and also recorded the highest fatalities across all user groups.
- In terms of victims, persons made up 51% of deaths, pedestrians accounted for 23%, while cyclists had the lowest fatality rate. 
- The top contributing factor to accidents was driver inattention or distraction (26%), followed by unspecified factors (20%), failure to yield right-of-way (11%), following too closely (8%), and unsafe speed (6%). 
- However, when looking at fatalities, the leading factors shifted, with unspecified causes (31%), unsafe speed (25%), and driver inattention (12%) being the most significant contributors.

## Recommendations and Conclusions 

The findings suggest that reducing collisions and fatalities in New York City requires a multifaceted approach. Authorities should strengthen driver awareness campaigns to tackle inattention and distraction, and improve speed enforcement, particularly in high-risk zones like Belt Parkway. 

The large percentage of “unspecified” contributing factors highlights the need for better police reporting and data accuracy. Additionally, pedestrian and cyclist safety measures should be expanded, given their vulnerability in urban traffic. 

Public education on safe driving practices should target high-risk time periods, such as afternoon rush hours and weekend nights, to further reduce accidents.

In conclusion, motor vehicle collisions in New York City are primarily driven by inattention, unsafe speed, and risky driving behaviors, with passenger vehicles responsible for the majority of cases. Targeted enforcement, improved reporting, safety campaigns, and infrastructure interventions can help reduce accidents and protect all road users, ultimately making New York City streets safer for everyone.

### Connect with me on LinkedIn: 
www.linkedin.com/in/sopuluchukwu-ugwu
