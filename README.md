# Swire-Coca-Cola(Predictive-Maintenance)

## Introduction

Unplanned equipment failures disrupt industrial operations, leading to significant financial losses, operational inefficiencies, and resource strain. This project focuses on predictive maintenance using machine learning and advanced analytics to anticipate maintenance needs, identify high-risk equipment, and schedule proactive interventions. The solution minimizes downtime, enhances resource optimization, and improves decision-making processes by leveraging operational and maintenance data.

## Business Problem

Industrial equipment downtime presents significant challenges that impact efficiency, costs, and resource management. Unexpected failures disrupt operations, leading to delays, underutilization of resources, and cascading inefficiencies across interconnected processes. These unplanned breakdowns also escalate operational expenses through emergency repairs, mismanagement of spare parts, and halted production cycles. Moreover, reactive maintenance substantially strains resources, diverting time and effort from strategic, long-term objectives. Addressing these challenges is critical to ensuring operational continuity, cost-effectiveness, and sustainable growth.


## Project Objective

The transition from reactive maintenance to predictive strategies ensures smooth operations, reduced costs, and optimal resource utilization.

## Analytics Approach

This project adopted a comprehensive data-driven approach to address equipment maintenance challenges. Our analytical approach aimed to extract actionable insights and establish a robust framework for predictive maintenance. We began with exploratory data analysis to uncover patterns in equipment failures and maintenance schedules. Next, we focused on feature engineering, introducing key metrics like the FAILURE_RISK_SCORE and maintenance frequency, which helped pinpoint high-failure-risk components. Using these features and historical data, we applied machine learning to predict future maintenance needs, flagging high-risk equipment and forecasting maintenance dates.


## Solution

Our group implemented a robust predictive maintenance framework to address the critical challenge of unplanned equipment downtime and its associated costs. By leveraging historical operational and maintenance data, we developed a Failure Risk Score to identify high-risk equipment and prioritize maintenance activities. This score combines metrics such as Time Used to Lifespan Ratio, Maintenance Frequency, and Maintenance Duration Deviation, enabling a comprehensive evaluation of equipment reliability.
Additionally, we utilized supervised learning techniques to predict future maintenance dates, ensuring timely preventive actions. Our model forecasts each machine's next five maintenance dates, empowering stakeholders to proactively schedule resources, minimize downtime, and enhance overall operational efficiency.
To support real-time decision-making, we developed interactive Power BI dashboards, offering stakeholders an intuitive interface to monitor equipment status, risk levels, and upcoming maintenance schedules across all production locations. These dashboards include functionality for email alerts, ensuring that preventive measures are triggered automatically when risk thresholds are met.
Finally, our solution extends beyond immediate operational improvements by recommending integrating IoT sensor data for dynamic feedback, further enhancing predictive accuracy. This comprehensive approach mitigates financial losses, optimizes resource allocation, reduces operational strain, and fosters a culture of proactive maintenance across the organization.


## Key Features
Failure Risk Score:
  Quantifies the likelihood of machine failure, helping prioritize maintenance needs.
  Combines operational data and maintenance patterns to create a robust metric.
Maintenance Forecasting:
  Predicts the following five maintenance dates for each piece of equipment.
  Flags high-risk equipment requiring urgent attention.
Real-Time Insights:
  Power BI dashboards provide actionable insights for monitoring equipment status, upcoming maintenance, and failure risk levels.


## Contribution

I contributed significantly to the project by leading the Exploratory Data Analysis (EDA) and Feature Engineering efforts, creating an interactive Power BI dashboard, and predicting maintenance requirements using statistical methods. During EDA, I analyzed the dataset to identify trends, patterns, and anomalies related to equipment maintenance and failures, uncovering key insights such as high-risk equipment and recurring maintenance patterns. For feature engineering, I developed advanced metrics like the FAILURE_RISK_SCORE, which quantified failure likelihood based on TIME_USED_TO_LIFESPAN_RATIO, MAINTENANCE_FREQUENCY, and MAINTENANCE_DURATION_DEVIATION. I also predicted future maintenance dates statistically, leveraging calculated intervals and past maintenance data to forecast upcoming requirements. To enhance visualization and decision-making, I created an interactive Power BI dashboard with a comprehensive site-level overview and a dedicated page predicting maintenance needs for equipment due within the next 30 days. This integrated approach empowered stakeholders with actionable insights to optimize operations, reduce downtime, and improve resource planning.


## Business Value

The implementation of predictive maintenance strategies significantly enhances operational efficiency, reducing unplanned downtime and associated costs. By forecasting maintenance needs, the project directly addresses potential annual revenue losses, cutting a projected $60M loss by $27M.

The Failure Risk Score and predictive models empower decision-makers to prioritize high-risk equipment, ensuring timely interventions and preventing catastrophic failures. Identifying critical maintenance areas, such as conveyors and packaging lines, ensures resources are allocated where they are most needed, optimizing both performance and budget.

Additionally, the integration of real-time, interactive dashboards in Power BI offers stakeholders a comprehensive view of equipment health and upcoming maintenance activities across all production sites. Features like email alerts for preventive measures equip the In-Process Control (IPC) team with actionable insights, fostering proactive rather than reactive maintenance practices.

Proposing the incorporation of IoT sensor data lays the groundwork for dynamic feedback, further improving predictive accuracy. This scalable solution not only enhances immediate operations but also establishes a robust framework for long-term strategic planning, aligning business goals with technological advancements.

## Challenges



**Data Completeness**:- Significant portions of critical data, such as functional area nodes and maintenance intervals, were missing or incomplete. This necessitated advanced imputation techniques, including NLP-based inference and statistical imputations, to fill gaps without introducing bias.

**Feature Selection and Engineering**:- Managing a large dataset with numerous interdependent features presented difficulties in identifying the most relevant predictors for maintenance and failure risk. Extensive iterations were required to optimize the Failure Risk Score and ensure meaningful insights.

**Model Optimization**:- Tuning hyperparameters for time series models and survival analysis algorithms was time-consuming, requiring considerable computational resources. Balancing model performance and runtime efficiency was a critical challenge.

**Data Visualization and Integration**:- Creating interactive and insightful dashboards in Power BI posed technical challenges, particularly in linking dynamic visualizations across multiple production locations and incorporating alerts for upcoming maintenance tasks.

**Collaboration and Coordination**:- With each team member specializing in different aspects of the project (EDA, modeling, dashboards, and business interpretation), aligning individual efforts into a cohesive workflow required strong communication and iterative reviews.

**Resource Constraint**:- Limited computational resources occasionally hindered large-scale simulations and extended analysis, necessitating creative workarounds and prioritization of tasks.



## Lessons Learned

Through this project, I gained valuable insights into data preprocessing and feature engineering, including handling missing values and creating impactful features like the Failure Risk Score to enhance model performance. 
The structured analytical approach taught me the importance of exploratory data analysis, survival analysis, and time series modeling, as well as leveraging NLP for imputing missing data. 
Another crucial learning was the role of visualization and stakeholder communication. Developing interactive dashboards in Power BI taught us how to translate technical findings into actionable insights. 
Creating user-friendly interfaces with real-time monitoring capabilities, coupled with automated email alerts, reinforced the significance of delivering solutions that are not just technically sound but also practically implementable for business users. Overall, this project provided practical experience in bridging theoretical knowledge with real-world applications, preparing me for multidisciplinary projects in the industry.

Results that help the business (Swire-Coca-Cola) requirements.

**[EDA Notebook](https://github.com/gnair60/Home-Credit-Capstone/blob/main/EDA.ipynb)**

**[Modeling Notebook](https://github.com/gnair60/Home-Credit-Capstone/blob/main/Modelling.ipynb)**

**[Presentation]([https://github.com/gnair60/Home-Credit-Capstone/blob/main/Capstone_Presentation.pdf](https://github.com/gnair60/Swire-Coca-Cola-Predictive-Maintenance-/blob/main/Capstone_Presentation.pdf))**
