# Metrocar-Funnel-Analysis_SQL_Tableau
Unlocking the Road to Seamless Ride-Hailing: Funnel Analysis Mastery for Metrocar with SQL and Tableau


## Funnel Analysis :Metro Car

### Project Background and Context

Metrocar is a ride-sharing app that connects riders with drivers through a user-friendly mobile application. As an intermediary platform, Metrocar aims to provide a seamless ride-hailing experience for its users. To ensure continuous improvement and optimization of their services, Metrocar has initiated the Funnel Analysis Mastery Project. This project involves analyzing the customer funnel of Metrocar to identify areas where the user journey can be enhanced and streamlined.

Metrocar's customer funnel consists of several stages, including app download, signup, ride request, driver acceptance, ride, payment, and review. At each stage, there is potential for users to drop off, which can indicate pain points or areas requiring improvement. By conducting a comprehensive funnel analysis, Metrocar aims to gain valuable insights into user behavior and identify opportunities for enhancing the customer experience.

### Objective

The main objective of the Funnel Analysis Mastery Project is to analyze Metrocar's customer funnel using SQL for data analysis and either Tableau or Google Sheets for data visualization. The project aims to answer the stakeholders' business questions and provide actionable recommendations based on the insights obtained from the data analysis.

The stakeholders have raised specific business questions that will guide the analysis and uncover valuable insights for improving specific areas of the customer funnel. By addressing these questions, the project aims to identify bottlenecks, drop-off points, and areas of potential friction within the funnel. These findings will enable Metrocar to make informed decisions and implement targeted strategies to optimize user engagement, increase conversion rates, and enhance the overall ride-hailing experience.

Through a comprehensive analysis of the dataset, the project will provide Metrocar with actionable recommendations to address the identified pain points and improve the customer funnel. The recommendations will be supported by insights derived from the data, enabling Metrocar to prioritize initiatives that will have the greatest impact on customer satisfaction, retention, and growth.

By leveraging the power of data analysis and visualization, the Funnel Analysis Mastery Project aims to empower Metrocar with the knowledge and insights necessary to optimize their ride-sharing platform, drive user engagement, and deliver an exceptional experience to riders and drivers alike.

### Deliverables

1. **Funnel Analysis Report**: A comprehensive report that presents the findings of the funnel analysis conducted on Metrocar's customer funnel. The report should include insights and recommendations based on the analysis, addressing the stakeholders' business questions. It should provide a detailed overview of each stage of the funnel, highlighting drop-off points, conversion rates, and areas for improvement.

2. **Data Analysis**: A detailed analysis of the dataset using SQL. This analysis should cover various aspects of the customer funnel, including app downloads, sign-ups, ride requests, driver acceptance, rides, payments, and reviews. The analysis should provide insights into user behavior, conversion rates, platform performance, age group dynamics, and other relevant metrics.

3. **Data Visualizations**: Visual representations of the funnel analysis using either Tableau or Google Sheets. The visualizations should effectively communicate the key findings and trends identified in the data analysis. They should include charts, graphs, and other visual elements that help stakeholders understand the data and draw meaningful conclusions.

4. **Recommendations**: Actionable recommendations based on the insights derived from the data analysis. These recommendations should address the areas for improvement and optimization identified in the customer funnel. They should be supported by the data insights and provide clear steps that Metrocar can take to enhance the user experience, increase conversion rates, and improve overall business performance.

5. **Presentation**: A presentation summarizing the findings, insights, and recommendations from the funnel analysis. This presentation should be visually appealing, concise, and well-structured to effectively communicate the key points to stakeholders. It should highlight the most important findings, explain the rationale behind the recommendations, and provide an opportunity for stakeholders to ask questions and engage in discussions.

### Analysis Approach and Results

To conduct the funnel analysis of Metrocar, the provided dataset was accessed using the provided link, and SQL was used for data exploration. Several initial questions were answered to understand the validity of the dataset and gain insights into the data. These questions included identifying the steps of the funnel that required research and improvement and identifying specific drop-off points that prevented users from completing their first ride.

Additionally, the analysis focused on understanding the performance of different platforms (iOS, Android, and web) to recommend where to focus the marketing budget. Age groups were also analyzed to determine their performance at each stage of the funnel and identify the target customer age group. The distribution of ride requests throughout the day was examined to provide insights into surge pricing strategies.

To conduct the funnel analysis, SQL was used to compute statistics and extract insights for each stage of the funnel. The 'WITH' statement in SQL was utilized to gather insights for each funnel stage, and the 'UNION' operation was employed to combine the results sequentially according to the funnel stages. The resulting insights were then exported as a CSV file for further analysis and visualization.

Tableau was used to visualize the funnel analysis data. Worksheets were created in Tableau based on the extracted insights from the CSV file. These worksheets facilitated the visualization of key metrics such as customer retention rate, customer drop-off rate, app downloads by age group and platform, user count in each funnel stage by age range, app download trends by different platforms, and more. The worksheets were then utilized to build interactive dashboards, and these dashboards were combined to create a comprehensive story that presented the findings and recommendations derived from the funnel analysis.

Overall, the analysis provided valuable insights into the Metrocar customer funnel. It identified areas for improvement and highlighted platform performance, age group dynamics, and ride request distribution patterns throughout the day. These insights will guide decision-making to optimize the customer funnel, enhance user experience, and drive business growth for Metrocar.

### Insights for Optimization

**Customer Retention/Dropoff (Percentage of Previous and Percentage of Top):** The analysis of customer retention and dropoff rates reveals interesting insights. When considering the Percentage of Previous (POP) metric, we observe that approximately 51% of users successfully complete rides and payments. However, it is worth noting that the feedback rate is high at around 70%, suggesting that there is potential to improve conversion rates and leverage user feedback to enhance the overall user experience and engagement.

On the other hand, analyzing the Percentage of Top (POT) metric, we find that 52.55% of users request rides, but only 26.40% of them complete the payment process. This indicates a significant dropoff in conversion rates and emphasizes the need to focus on improving the customer journey and increasing the feedback rates, which currently stand at 18.42%.

Further investigation is required to understand why 50.77% (6,233 users) of the users complete the ride despite 12,278 users initially requesting the ride. Identifying the reasons behind this dropoff and finding ways to optimize the customer experience during the ride could lead to improved retention rates and overall satisfaction.

**App Downloads by Age Groups and Platforms:** The visualization of app downloads by age groups reveals that regardless of age, iOS dominates as the preferred platform for downloading the Metrocar app, accounting for over 60% of users. Android follows as the second most popular platform. It is important to consider these trends when devising marketing strategies and allocating budgets for the upcoming year.

**Number of User Counts in Each Funnel Stage by Age Range:** Examining the number of user counts in each stage of the funnel by age range, we find that the highest
