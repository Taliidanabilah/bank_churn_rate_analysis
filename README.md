# Bank Churn Rate Analysis

## Overview
This project primary goal is to mitigate customer churn by 10% within both one week and one month. We begin by meticulously analyzing churn reports from the previous quarter, gathering data on churn reasons, demographics, and transaction histories. Through comprehensive data cleansing and preprocessing, we ensure the accuracy of our insights. Moving forward, exploratory data analysis (EDA) guides us in uncovering patterns and correlations within the churn data, aiming to identify key drivers of churn such as service dissatisfaction or competitive offers. With these insights, we craft a strategy centered on targeted interventions and retention initiatives, such as personalized offers or enhanced customer service. Implementation of these strategies is swiftly executed, accompanied by continuous monitoring and refinement based on real-time feedback. Our overarching objective is to not only reduce churn rate but also foster improved customer retention, driving sustained revenue growth and solidifying the bank's competitive edge through a data-driven approach.

## SMART Framework
1. Specific: Participating in important role to create the bank's next quarter strategy making where the goal is decreasing the bank's customer churn number from the last quarter customer churn reports. 

2. Measurable: establish measureable metrics to track progress and sucess by this case in decreasing the churn rate number to 10%
      
3. Achievable: Analyze relevant data of customer churn number form the last quarter reports and making insight that could be utilized for the next quarter business strategy
    
4. Relevant: Making sure that the insight could give impact and relevant to the Bank's situation and possible to implemet

5. Time-bound: Creating the insights from the analysis in 1 week and make sure that are ready to implement within 3 weeks ahead. Making this project is ready to implemented within 1 month in total

## Conclusion:

In conclusion, based on the data analysis conducted, several key points have been identified to inform the next car sales strategy:

1. From data that we've been analyze we can see that female has contributed most number of churn rate. Despite being a minority in the overall customer base, female customers have a higher churn rate compared to male customers. The data shows that 1139 out of 4542 (25.06%) female customers churned, whereas only 898 out of 5454 (16.45%) male customers churned. This suggests that female customers may be more likely to churn compared to male customers, indicating a potential need for targeted retention efforts within this demographic.
 
2. Knowing the gender distribution among churned customers can help in designing targeted marketing strategies. For instance, if there are discernible differences in churn behavior between genders, marketing campaigns could be tailored accordingly to address the specific needs or preferences of male and female customers. Male and female customers may have different preferences for different products or services, which could account for the gender gap in churn rates. In order to better serve the demands of both male and female consumers, it can be helpful to analyze the kinds of goods and services that each gender prefers.

3. The age group of 40-49 years shown the highest churn rate, with more than 800 customers churning. This indicates that individuals in their 40s may be particularly able to switching banks or discontinuing services, suggesting a need for targeted retention efforts within this demographic.

4. Germany has the highest total number of churned customers (814), followed by France (810), and Spain (413). However, when considering the total customer base in each country, Germany has a smaller total number of customers compared to France and Spain. This indicates that the churn rate is relatively higher in Germany compared to France and Spain. We can suggest to implement more efforts and strategy in Germany Since its contribute a lot for the customer's churn number by  Implement targeted customer retention strategies specifically tailored for the German market, develop localized marketing campaigns that resonate with the German customer base,continuously monitor and track churn rates in Germany, as well as the effectiveness of any implemented strategies,evaluate the product or service offering in the German market to ensure it meets customer expectations and remains relevant and preferable.

5. From the customer's balances perspective, as we can see fom the correlation test using chi-square method. the implication is that customers with higher balances have a higher churn rate compared to those with lower balances. This suggests a negative correlation between balance and churn decision: as the balance increases, the likelihood of churn also increases. Therefore, despite the significant association between balance and churn decision, it's important to note that the direction of this association is negative. This insight could inform targeted retention strategies for customers with higher balances to reduce churn rates and retain valuable customers

6. From the number of product that customer's have, as we can see from the statistic test between its correlation with churn decision, customers with more products are at a higher risk of churning. Therefore, strategies aimed at retaining these customers should be prioritized. This might include personalized retention offers, enhanced customer service, or targeted marketing campaigns to increase customer engagement and loyalty. Conversely, customers with fewer products may exhibit higher retention rates, but efforts should still be made to ensure their satisfaction and loyalty to prevent churn.

7. From the activity perspective, the churn rate for inactive members is approximately 26.9%, while the churn rate for active members is approximately 73.1%. This indicates a strong negative correlation between activity (IsActiveMember) and churn rate. Specifically, inactive members are more likely to churn compared to active members. It means, we need to develop strategies to develop the customer activity

 
## File Descriptions
The project consists of two files:
- **Churn_Modelling.csv:** The raw data source in CSV format.
- **Churn_Modelling_cleaned.csv:** Cleaned data, including modifications to columns and removal of unused columns based on domain knowledge.
- **bank_churn_rate_analysis:** A Jupyter notebook script containing data loading, data cleaning, analysis, and calculations (including descriptive and inferential statistics, as well as data visualization), and conclusion (including concise and clear conclusions, recommendations, or answers to the problem, along with summarizing the key insights from the analysis and calculations). 

## References: 
- Dashboard:<a href="https://public.tableau.com/app/profile/taliida.nabilah/viz/ChurnRateAnalysis_17079325588300/Dashboard1"> Tableau</a>.  
- Dataset: <a href="https://www.kaggle.com/code/carlosalvro/bank-churn-analisys"> Kaggle</a>.

---
For any questions or suggestions, please contact me at <a href="taliida.nabilah@gmail.com"> taliida.nabilah@gmail.com</a>.
