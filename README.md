# An Analysis of Kickstarter Campaigns

### Overview of Project
A comprehensive dataset of Kickstarter Campaigns from around the world. Contains information such as pledged amounts of money and goals set for the campaign. This analysis contains pivot tables and charts comparing amounts of money raised, types of campaigns, average donations, success vs failure etc.
It also contains the averages, medians, standard deviations, and the IQR of successful vs failed kickstarters so that Louise can gauge a proper goal for her own campaign.
### Analysis: 
Louise's Great Britain play budget is 4,000 euro, however this is outside the range of outliers for the pledged amount. So Louise should try to get her play produced for less than 4,000 euro, as half of the campaign goals are less than 2,000 euro (which is just over the 3rd quartile for amounts pledged).
### Challenges:
I ran into a problem with my data set severely skewed the findings. I believe that I lost half of my data in the kickstarter page or some other unknown data loss occurred. I did my best to overcome the problem by looking at my countifs function to see if that was the problem. I learned that my countifs function was correct as it was, the data I was trying to reference just doesn't seem to exist on my kickstarter sheet.

### Results:
1. Theater Outcomes by Launch Date:
2. ![image](https://user-images.githubusercontent.com/106174279/180090863-19853269-b575-475e-8043-8b7c23fc1642.png)

3. Outcomes Based on Goals:
![image](https://user-images.githubusercontent.com/106174279/180090798-d89c4fcb-dfe3-4be1-a72e-df5ffe6e6d30.png)

### Limitations of the dataset:
### Additional tables or graphs to be added:
* Louise can eliminate the data points with funding for a theater as she only needs funding for a play
There are a few large values driving the data (maybe failed kickstarters with really high goals?) the standard deviations are all roughly twice the IQR in each distribution except for the failed kickstarters where the SD is three times the IQR.
!
