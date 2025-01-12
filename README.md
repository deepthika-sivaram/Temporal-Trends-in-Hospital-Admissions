# Temporal-Trends-in-Hospital-Admissions

**Introduction**

In recent years, air pollution has emerged as a critical public health issue, with significant implications for respiratory health. Given the escalating levels of pollution in urban areas, understanding its impact on hospital admissions for respiratory illness is crucial for effective healthcare planning and resource allocation.
In this phase, by analyzing historical data on air quality and hospital admissions, we aim to identify patterns and correlations that can inform healthcare providers and policymakers on the preparedness of healthcare systems during periods of heightened pollution, enabling more effective resource allocation and improved patient care.

**Problem Statement**

Title: Temporal Trends in Hospital Admissions: The Influence of Air Quality on Respiratory
Health
In this project, we aim to investigate the relationship between air quality and hospital admissions for respiratory illness. By examining the relationship between air pollutants (e.g., PM2.5, PM10, NO2, SO2) and respiratory conditions, the goal is to determine whether poor air quality contributes to increased hospitalizations. This will help provide insights into the health impact of air pollution over time.

**Key Questions:**
• How do changes in pollution levels affect hospital admissions for respiratory illness?
• What time-based patterns can be identified in the relationship between air quality and respiratory health outcomes?

**Background of the problem**

Air pollution is a critical public health issue worldwide, with pollutants like particulate matter, nitrogen dioxide , sulfur dioxide , and carbon monoxide contributing to serious health problems. These pollutants, mainly from vehicles, industries, and fossil fuel combustion, disproportionately affect individuals with pre-existing conditions such as asthma and heart disease, leading to increased hospital admissions and premature deaths, especially in urban areas.

Key statistics include:
• WHO estimates 7 million deaths annually from air pollution.
 • 20-30% increase in hospital admissions for respiratory and cardiovascular diseases in heavily polluted cities.
• 1.8-year reduction in life expectancy due to long-term exposure to air pollution.
• 5-10% annual increase in hospital admissions related to air quality issues in highly polluted countries.
This project aims to develop a classification model that uses historical pollution data and hospital admission records to forecast future admissions for respiratory illness based on air quality levels. By identifying the correlation between poor air quality and hospital admissions, this model can assist healthcare providers and policymakers in effectively allocating resources, preparing for potential surges in respiratory-related hospitalizations, and issuing timely health warnings to the public. Ultimately, the project seeks to provide valuable insights into the health impacts of air pollution, informing long-term policy decisions aimed at mitigating air quality issues and protecting public health.

**Significance**

• Enhancing Public Health: Forecasting hospital admissions related to respiratory illnesses based on pollution levels enables healthcare systems to prepare for increased patient volumes during highpollution days, ensuring sufficient medical staff and resources are available to save lives.
• Supporting Vulnerable Populations: The project aims to protect vulnerable groups—such as children, the elderly, and those with pre-existing conditions—by allowing public health officials to issue timely warnings and implement preventive measures when pollution levels rise.
• Optimizing Resource Allocation: Predicting surges in respiratory-related admissions helps hospitals allocate resources efficiently, manage operations effectively, and reduce overcrowding, ensuring all patients receive necessary care.
• Raising Public Awareness: This initiative aims to raise awareness about the serious health risks posed by air pollution, potentially motivating governments and communities to take stronger actions to mitigate its impact.
• Promoting Data-Driven Decision-Making: By integrating historical pollution data with health records, the project highlights the importance of data in developing classification models that enhance decision-making and improve health outcomes related to respiratory illnesses.

**Rationale for Investigation**

• Escalating Health Issues: Air pollution causes millions of deaths annually and increases respiratory and cardiovascular diseases. Understanding its impact on hospital admissions for respiratory illnesses is vital for managing these health risks, particularly for vulnerable populations.
• Predictive Tools: Current healthcare systems often lack advance warning for rising admissions related to poor air quality. Predictive models based on pollution data can help hospitals prepare for surges, enhancing care quality.
• Policy Influence: Robust data on pollution’s effects on hospital admissions can inform policymakers, supporting stricter regulations and effective public health guidelines to protect community health from the adverse effects of poor air quality.
Potential Impact
• Enhanced Healthcare Preparedness: Predicting hospital admissions related to respiratory illnesses based on pollution levels allows healthcare facilities to optimize resource allocation, ensuring adequate staff and equipment during high-pollution periods, leading to better patient outcomes.
• Improved Public Health Responses: The project can issue timely alerts, prompting individuals to take protective measures, such as staying indoors, thereby reducing exposure to harmful air quality.
• Targeted Interventions for Vulnerable Populations: By identifying high-risk periods, the project helps healthcare providers focus on vulnerable populations, such as children and the elderly, ensuring they receive prompt care.
• Data-Driven Decision Making: Demonstrating the value of data in predicting health outcomes related to air quality can encourage a culture of evidence-based decision-making in healthcare and policy, driving further research and investment in predictive analytics.

**Data Sources**

Dataset: https://www.kaggle.com/datasets/ashishsahani/hospital-admissions-data/code

The dataset utilized for our project is sourced from Kaggle and comprises significant records pertaining to hospital admissions, pollution and mortality. It consists of 3 csv files namely Admissions, Pollution and Mortality. Admissions dataset contains a total of 15,757 rows and 56 columns, which include various attributes such as the admission date, discharge date, type of admission, and patient outcomes. The pollution dataset consists of 737 rows and 29 columns which include features like NO2 MAX, C02 MAX and prominent pollutant. The mortality dataset is neglected for our research as it might not have much influence on the classification problem. These data points are essential for analyzing the relationship between patient admission and pollution levels, as they will provide crucial insights into how environmental factors impact health outcomes.
