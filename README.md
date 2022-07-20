# An Analysis of Kickstarter Campaigns

### Overview of Project
A comprehensive dataset of Kickstarter Campaigns from around the world. Contains information such as pledged amounts of money and goals set for the campaign. This analysis contains pivot tables and charts comparing amounts of money raised, types of campaigns, average donations, success vs failure etc.
It also contains the averages, medians, standard deviations, and the IQR of successful vs failed kickstarters so that Louise can gauge a proper goal for her own campaign.
### Analysis: 
Louise's Great Britain play budget is 4,000 euro, however this is outside the range of outliers for the pledged amount. So Louise should try to get her play produced for less than 4,000 euro, as half of the campaign goals are less than 2,000 euro (which is just over the 3rd quartile for amounts pledged).
According to the data, the best time * Louise can eliminate the data points with funding for a theater as she only needs funding for a play
There are a few large values driving the data (maybe failed kickstarters with really high goals?) the standard deviations are all roughly twice the IQR in each distribution except for the failed kickstarters where the SD is three times the IQR.
### Challenges:
I ran into a problem with my data set severely skewed the findings. I believe that I lost half of my data in the kickstarter page or some other unknown data loss occurred. I did my best to overcome the problem by looking at my countifs function to see if that was the problem. I learned that my countifs function was correct as it was, the data I was trying to reference just doesn't seem to exist on my kickstarter sheet. Next, I downloaded the original sheet for the second time to see if I still got the same results and I did. As such I decided that I would just work with the data that I had available to me. However, I did meet with the TA, Class instructor, and a tutor while I was looking for assistance and that helped me realize how useful those resources are to me. 

### Results:
1. Theater Outcomes by Launch Date:
![image](https://user-images.githubusercontent.com/106174279/180090863-19853269-b575-475e-8043-8b7c23fc1642.png)
According to the data, the best time to launch a kickstarter campaign is in May. Anytime after May looks like the results drop off. In fact, October has an unusual spike in failed kickstarters which suggests that starting a campaign in October is not the best idea. However, during the fall months (Sept-Nov), there were no canceled kickstarter campaigns.
2. Outcomes Based on Goals:
![image](https://user-images.githubusercontent.com/106174279/180090798-d89c4fcb-dfe3-4be1-a72e-df5ffe6e6d30.png)
Again, my outcomes based on goals section seems out of whack so I hesitate to say this data points are valid. I will do my best to recognize insights despite of the limitations. According to the chart, the highest number of successful kickstarter campaigns had a goal of somewhere between $1,000-$4,999. 546 campaigns found success when they were between this number. Suprisingly, 273 campaigns failed when their goal was less than $1,000 while 108 were successful. This seems to suggest that there is a sweet spot when it comes to setting a goal amount. Seeing as how Louise's goal is $4,000 she should be able to reach her goal especially if she launched the campaign in the month of May.
### Limitations of the dataset:
Again, the dataset is limited in that it would not show the canceled plays in the outcomes based on goals page. Also, the data would be more robust if it included average budget categories. That way Louise would know exactly what she would be spending her money on and where to alocate it all so that the money she did raise would not go to waste.
### Additional tables or graphs to be added:
This dataset would be far more insightful if it included graphs that marked the average pledged amount. That way Louise has a more specific goal to aim for that will help break down her big goal into smaller, more manageable bits. Another interesting chart would be an comparing the names of the plays to rate of success. This way she could see if one of the reasons plays were being canceled was due to lack of interest from potential play watchers. While liking the title of something is certainly subjective, there may be a pattern in word placement or certain words used that audiences liked better than others.
