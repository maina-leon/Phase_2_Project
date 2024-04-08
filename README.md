 UNDERSTANDING YOUR HOME VALUE
 ![image](https://github.com/Jane133/Group_7_Phase_2_Project/assets/144534856/ecadae7a-23f3-4245-870a-83b299074a73)
Authors: Jane Martha, James Njoroge, Leon Maina, Daniel Wahome, Magdalene Ondimu, Faith Mwenda.
# Overview
Your home's value is influenced by various factors such as size, location, condition, and amenities. Our analysis aims to uncover the key drivers of house prices to help you make informed decisions.
# Business Problem
The main problem for homeowners is the failure to make strategic decisions in investing for the proper renovation of their rental homes. The homes end up depreciating hence losing customers. The homeowners lack knowledge on how to be responsible owners and hence end up suffering a great loss.
# Key Question
What are the Assessment criteria, and policies for renovations?
What factors are involved in renovations?
How do you optimize returns for homeowners?
# Data Understanding and Analysis
Data was obtained from an existing dataset, the King County House Sales. This dataset was provided for this project. The data is a csv file called kc_house_data.csv. 
The data contains 21597 entries and 21 columns. The datatypes are float(5), integer(10) and object(6). 
# Methods
Multiple linear regression modeling is used in this study to provide homeowners with useful information as they navigate the challenging real estate market. As market analysts specializing in real estate, our objective is to discern the intricate relationships among diverse property attributes and their impact on the selling price of properties. By exploring the King County House Sales data collection, we intend to provide homeowners with enlightening guidance on how to raise the estimated value of their homes by making thoughtful improvements
# Results
The heatmap shows the correlation between the target variable in this case price and predictive features which are sqft_living, sqft_lot, and age.
The lighter the color the stronger the correlation.
sqft_living: 0.682342 (Strong positive correlation) sqft_lot: 0.084739 (Weak positive correlation) Age: -0.048722 (Weak negative correlation)
![image](https://github.com/Jane133/Group_7_Phase_2_Project/assets/144534856/e5b18691-da8c-4327-b9b4-bf4a5e503354)


This scatter plot shows the lineality between the transformed predictor(log_sqft_living) and the target variable (log_price), this is essential for linear modeling.

![image](https://github.com/Jane133/Group_7_Phase_2_Project/assets/144534856/7a1f64c9-222e-4d59-a403-447ceda908c0)

The qq(quantile-quantile) assesses whether the residuals(the differences between observed and predicted values)are normally distributed, this shows they are normally distributed.
![image](https://github.com/Jane133/Group_7_Phase_2_Project/assets/144534856/cca42834-6fb9-4dbb-9f35-d00cf9f334d1)


# Conclusion
Be keen observation of the current trend
Invest in proper and quality renovations
Give priority to areas that will give you more profit
Ensure frequent maintenance
To avoid costs caused by customers’ damage during their occupation in the houses, set extra charges for every damage by customers during the stay in.
Real estate owners should be ready to take risks when it comes to the customers' interest. They should stay ahead and know the current trends to boost the quality of houses and meet customers expectations.
# For more information
Please contact the authors jane.martha@student.moringaschool.com, james.njoroge1@student.moringaschool.com, ngarileon@gmail.com, daniel.wahome@student.moringaschool.com, magdalene.ondimu@student.moringaschool.com, faith.mwenda@student.moringaschool.com


