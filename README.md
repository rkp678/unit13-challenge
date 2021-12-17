# Unit 13 Homework: The Power of the Cloud and Unsupervised Learning - Rachel Pierce
## December 2021

## *Instructions:*
### Two Options:
1. Option 1: Robo Advisor for Retirement Plans (SELECTED)  
2. Option 2: Clustering Crypto

#
## *Please refer to the following documents in GitHub:*
- The **RecommendPortfolio, riskLevel and RoboAdvisor2** zip files for AWS Lex builds (bot, slot, and intent).  
- The **lambda_script.txt** and **lambda_function.py** files for the lambda code.

#

## Option 1: Robo Advisor
### Three Main Tasks
1. Initial Robo Advisor Configuration - completed.
2.  Build and Test the Robo Advisor - completed.
3.  Enhance the Robo Advisor with an Amazon Lambda Function - completed.

### Notes  
Using Lex, the chat bot worked well, but when I input the lambda code, I kept getting an error.  I reviewed the code numerous times, and received guidance from my instructor, but we still could not get the code to work.  I added notes in the code txt file for your reference.  A summary is below:  

- I added a "def validate_data" function to provide parameters for age (between 0 and 65) and investment amount (greater than or equal to $5,000).
- I added to the "def recommend_portfolio" function for data validation (get slots, return elicit_slot).  The homework template already included return data, which was confusing as my code required a different return function, so this may be where my code was not working properly.
- I added my final investment recommendation code using a "def get_investment_recommendation" function with all the risk levels (none, very low, low, medium, high, and very high).  As mentioned above, the homework template again already included return data, so this could be another area that was problematic.

Overall this was a good way to practice, even though the error code was frustrating.  I went back to the in-class lessons and ran some other bots for additional practice without getting an error, which was fun!  
  
Finally, please enjoy the baby yoda photos in the chat bot cards for risk levels.

![image](./images/babyyoda.png)   

