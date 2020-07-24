# User Behavior and A/A/B Test Analysis Project

## Project Description / Business Problem

> You work at a startup that sells food products. You need to investigate user behavior for the company's app.
First study the sales funnel. Find out how users reach the purchase stage. 

>Then look at the results of an A/A/B test. The designers would like to change the fonts for the entire app, but the managers are afraid the users might find the new design intimidating. They decide to make a decision based on the results of an A/A/B test.
The users are split into three groups: two control groups get the old fonts and one test group gets the new ones. Find out which set of fonts produces better results.
You'll be using the same dataset for general analytics and for A/A/B analysis. In real projects, experiments are constantly being conducted. Analysts study the quality of an app using general data, without paying attention to whether users are participating in experiments.

# Findings 
1. A further analysis should be done looking at potential errors occurring during the mainscreen and offerscreen stages based on the differing proportions amongst the control groups.
2. Need for improvements in retention at the offer screen as well as potential for improvement in getting customer's from purchasing the items that they have in their cart.
3. Based on the non-significant the A/B test results, stabilizing cumulative charts, the company should: Stop the experiment as the results don't show any improvement in  user conversion rates between the control groups and the experimental group
    - all relevant t-tests regardless of outlier presence: p > .05
    
  # Datsets Used
 Each log entry is a user action or an event.
 - EventName — event name
 - DeviceIDHash — unique user identifier
 - EventTimestamp — event time
 - ExpId — experiment number: 246 and 247 are the control groups, 248 is the test group
 
 # Figures
 [Figure 1](https://github.com/dannygarcia193/AAB-Test_UserAnalytics_Project/blob/master/images/Screenshot_221.png)
 [Figure 2](https://github.com/dannygarcia193/AAB-Test_UserAnalytics_Project/blob/master/images/Screenshot_222.png)
 [Figure 3](https://github.com/dannygarcia193/AAB-Test_UserAnalytics_Project/blob/master/images/Screenshot_223.png)
 [Figure 4](https://github.com/dannygarcia193/AAB-Test_UserAnalytics_Project/blob/master/images/Screenshot_224.png)
 [Figure 5](https://github.com/dannygarcia193/AAB-Test_UserAnalytics_Project/blob/master/images/Screenshot_225.png)
 [Figure 6](https://github.com/dannygarcia193/AAB-Test_UserAnalytics_Project/blob/master/images/Screenshot_226.png)
 [Figure 7](https://github.com/dannygarcia193/AAB-Test_UserAnalytics_Project/blob/master/images/Screenshot_227.png)
