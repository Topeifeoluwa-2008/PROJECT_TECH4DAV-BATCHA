# PROJECT_TECH4DEV-BATCHA

# Analyzing the Impact of Lifestyle Factors on Sleep Quality and Duration In Support of SDG Goal 3: Good Health & Well-being

## [Introduction](Introduction)
In a world where work demands, physical inactivity, and high stress are the norm, how much do our daily choices affect the quality and length of our sleep? 
Half of the world's population report struggling with sleep due to lifestyle factors like stress, occupation demands, or even weight. Poor sleep affects us all, 
yet we often overlook the powerful influence our daily habits have on it.
Our project, “Analyzing the Impact of lifestyle Factors on Sleep Quality and Duration,” aims to explore how elements such as physical activity, occupation type, Body Mass Index (BMI),
and stress levels influence both the quality and duration of sleep. The insights drawn from this data-driven analysis 
will illuminate the often-hidden impact of our lifestyles on this critical component of health.
Good sleep is fundamental to health and well-being, making this study a valuable resource for individuals and policymakers alike in understanding how healthier lifestyle choices can lead to better sleep.
This project aligns with SDG Goal 3 – Good Health and Well-being, as it highlights how informed lifestyle adjustments can enhance sleep quality, supporting overall health and public well-being.

## [DataSet Overview](DataSetOverview)
Dataset includes 374 individuals with detailed information on sleep patterns and various lifestyle factors.

## Problem Statement
Many individuals struggle to maintain optimal health due to factors like high stress levels, inadequate sleep, and sedentary lifestyles, which can lead to issues such as obesity, hypertension, and sleep disorders. This dataset provides an opportunity to examine the relationships between these lifestyle factors and health indicators to identify common patterns and at-risk groups. The analysis will focus on identifying correlations among sleep quality, physical activity, stress levels, BMI, and health metrics (e.g., blood pressure and heart rate) to provide recommendations that can improve overall well-being.

## Data Sources

The dataset used in this analysis is derived from Kaggle, which was provided in a CSV format. [www.kaggle.com]

## Key Variable Used
1. Sleep Duration & Quality: Quantitative measures capturing how long and well each participant sleeps.
2. Lifestyle Indicators: To capture Quality of Sleep and Daily Steps
3. Physical Activity Level: Range from low to high, allowing analysis of activity’s effect on sleep.
4. Occupation Type: Various job roles to explore if specific professions impact sleep quality.
5. BMI Category: Weight classifications (e.g., normal weight, overweight, obese) for studying BMI’s relation to sleep.
6. Stress Levels: Measures of daily stress, offering insights into stress-sleep relationships.

## Data Transformation
To ensure that the data is suitable for analysis, the following transformation steps were taken:
-   Data Cleaning: To Check for any duplicate records, especially among fields such as occupation and demographic details, and remove any redundant entries.
-   Feature Engineering: I Created new variables that may provide additional insights, such as Bp Category and age band   
-   Normalization: Scale numerical fields like Sleep Duration, Physical Activity Level, and Heart Rate to ensure uniformity in the dataset.
-   Handling Missing Values: Although this dataset does not appear to have missing values, though there was a replace value such as Normal to Normal Weight on BMI column

## Methodology
## Tools Used
- Power Bi
   i. Power Query Editor for Data cleaning
  ii. Analysis
  iii. Visualization

## Data Visualization

![tech dev](https://github.com/user-attachments/assets/bd7129ca-85e3-4ab8-bb9d-f46e17e284b4)

![tech dev3](https://github.com/user-attachments/assets/077790a2-3075-43b9-aabd-a945512a3a22)

![tech dev4](https://github.com/user-attachments/assets/b6229298-7110-4b86-a33f-d376ef644f27)

![tech dev5](https://github.com/user-attachments/assets/166ed11e-1abd-41ed-8d50-1f50adc5d838)

### First Visualiation
This dashboard provides a comprehensive analysis of occupation Analysis and sleep Disorder, focusing on daily steps, 
quality of sleep, sleep disorders, and stress levels. 
The key metrics is displayed using a card visuals, cluster column charts and slicers
*   Average Daily Steps: The population's daily step count averages 6.82K.
*   Average Age: The age range centers around 42.18 years.
*   Total Sample Size: 374 individuals across 11 different occupations.
The visuals break down health indicators by occupation, including sleep quality and duration, 
stress levels, and disorders like sleep apnea and insomnia. Notably, sale representative exhibit higher 
levels of stress and poorer sleep quality. For instance, the data suggests that the software 
engineers may experience greater sleep disturbances and stress levels compared to other groups.
Additionally, heart rate data helps us analyze daily steps' variability, with spikes in step counts 
suggesting patterns in physical activity. Filters for BMI categories, occupation, and age bands allow 
a more focused analysis on specific demographics, supporting targeted health and wellness initiatives.

![tech dev2](https://github.com/user-attachments/assets/23377c2e-c198-45b4-983d-68aa65dd27c7)

![tech dev6](https://github.com/user-attachments/assets/fc11a18e-e077-48d6-bec9-36217a6cb971)

![tech dev7](https://github.com/user-attachments/assets/2abca514-487c-4ca7-a48c-4107aadd2445)

![tech dev8](https://github.com/user-attachments/assets/d0ab93a6-c05f-443f-901c-9c33c802f29a)

![tech dev9](https://github.com/user-attachments/assets/a132289e-ecf0-42d8-852e-7d99e649fe68)


### Second Visualiation
This dashboard focuses on various health metrics, providing insights into sleep duration,quality of sleep, and the effects of different health factors such as BMI, blood pressure (BP), and stress levels on sleep quality.
Key insights include is displayed using a card visual, cluster column chart and slicer
such as Average sleep duration, Heart Rate, Bp Category
*   Average Sleep Duration: The population has an average sleep duration of 7.06 hours.
*   Count of Heart Rate Measurements: The data includes 19 recorded heart rate values.
*   Sleep Quality by Stress Level and Gender: Higher stress levels correlate with lower sleep quality, 
with males generally experiencing lower sleep quality and higher stress levels compared to females.
*   Age and Sleep Quality: Older adults report higher sleep quality (7.5hours) compared to middle-aged (7.3hours) and younger adults (6.16hours).
*   BMI and Sleep Quality: The pie chart reveals that the majority of individuals are of normal weight, and this group also tends to report higher sleep quality compared to overweight and obese categories.
Blood Pressure and Sleep: Sleep quality varies slightly across BP categories, with those in the "Normal Weight" category reporting the highest sleep quality (7.57).
This dashboard can guide occupational health interventions by identifying a risk groups and patterns associated with lifestyle-related health issues.
 
## Conclusion
-  High-stress roles, like Sales Representatives, show poorer sleep and health metrics, while roles like Engineering report better sleep quality.
-  Higher stress levels correlate with lower sleep quality, reinforcing the need for stress management in demanding jobs.
-  More active individuals generally have better sleep and healthier BMI. Sedentary roles could benefit from programs encouraging movement.
-  Elevated blood pressure is associated with poorer sleep, emphasizing the need for cardiovascular monitoring in high-risk occupations.
-  Older adults and females report slightly better sleep quality, suggesting tailored wellness programs can improve outcomes.
-  Sleep issues vary by occupation, with high-stress roles facing greater risks, highlighting the need for workplace support.
This analysis summarily highlights the importance of targeted health interventions to improve sleep and well-being, tailored to the unique needs of each occupation. Addressing these lifestyle factors can lead to healthier, more productive workforces and support SDG Goal 3 – Good Health and Well-being.

## Recommendations
Based on the analysis, the following recommendations can be made: 
-  For occupations with lower physical activity (e.g., sales representatives), encourage daily exercise routines to improve sleep quality, standing desks or walking breaks, which will help integrate more movement into the day, supporting better physical health and sleep outcomes.
-  Implementing stress-relieving programs, such as mindfulness sessions or counseling, to support employees in managing stress, can in turn, positively impact both sleep duration and quality, particularly in high-stress professions.
-  For individuals at risk of sleep disorders, like insomnia or sleep apnea, provide sleep hygiene workshops to educate them on best practices for a restful night’s sleep. Where needed, recommend consultations with healthcare providers for professional support, to enhance sleep quality and overall health.
-  Regular health checks, focusing on metrics like blood pressure and BMI, are essential, especially for those in high-stress or sedentary jobs. Monitoring these metrics helps identify early signs of sleep-related health issues, allowing for timely interventions that can improve sleep and general well-being.
-  Develop personalized health and wellness plans tailored to each occupation to boost physical activity, manage stress, and promote healthy sleep practices, ensuring each occupational group receives support relevant to its unique lifestyle challenges.
These recommendations aim to boost healthier lifestyle choices, improve sleep quality, and enhance well-being across various occupational groups, aligning with SDG Goal 3 – Good Health and Well-being.



