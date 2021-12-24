# Unit 13 Homework: The Power of the Cloud and Unsupervised Learning - Rachel Pierce
## December 2021

## *Instructions:*
### Two Options:
1. Option 1: Robo Advisor for Retirement Plans (SELECTED)  
2. Option 2: Clustering Crypto

#
## *Please refer to the following documents in GitHub:*
- The **RecommendPortfolio, riskLevel and RoboAdvisor2** zip files for AWS Lex builds (bot, slot, and intent).  
- The **lambda_script_UPDATED.txt** and **lambda_function.py** files for the lambda code.

#

## Option 1: Robo Advisor
### Three Main Tasks
1. Initial Robo Advisor Configuration - completed.
2.  Build and Test the Robo Advisor - completed.
3.  Enhance the Robo Advisor with an Amazon Lambda Function - completed.

### Notes  
Using Lex, I created a chatbot and then imported my lambda code.  
- I added a "def validate_data" function to provide parameters for age (between 0 and 65) and investment amount (greater than or equal to $5,000).
- I added my final investment recommendation code using a "def get_investment_recommendation" function with all the risk levels (none, very low, low, medium, high, and very high).
- I added to the "def recommend_portfolio" function for data validation (get slots, return elicit_slot).  

The chatbot was demonstrated live to my instructor.

Please enjoy the baby yoda photos in the chat bot cards for risk levels.

![image](./images/babyyoda.png)   

