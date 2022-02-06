# Kickstarting with Excel

## Overview of Project
This project is to performing the analysis on Kickstarter campaign data using the Kickstarter dataset via Microsoft Excel tools. We will visualize campaign outcomes based on their launch dates and their funding goals.
### Purpose
The analysis is to help uncover how different campaigns fared in relation to their launch dates and their funding goals. That will help look into how the launch month and funding goals affect campaign outcomes and make future decision on launching potential fundraising goals.
## Analysis and Challenges
The analysis includes two technical analysis. The first one analyzes campaign outcomes based on their launch month and year. The second one analyzed campaign outcomes based on their goals.

### Analysis of Outcomes Based on Launch Date
The launch date could be critical to a fundraising, especially the launch season and month. Using the Kickstarter data set, we created the pivot table and chart to represent the relationship between launch time and campaign outcomes. Based on the counts of sucessful, failed and canceled outcomes through all years, we summarize the changes among different months using two filters of Category and years. We could also look into each year to reveal the relationship for specific year. Here, we filter the theater category taking into account of all years from 2009 through 2017 when data is available to overview the trends.

### Analysis of Outcomes Based on Goals
We would like to see if the campaign outcomes are related to the funding goal amount. Similarly, this analysis is conducted based on the percentages of successful, failed and canceled outcomes, respectively, within different funding goal ranges. Here, a filter has been applied to select the subcategory of plays only to focus on this field.

### Challenges and Difficulties Encountered
The analysis was completed smoothly with the instruction on website. In my daily work as a water resource engineer I did multiple analysis and modeling in excel using tables manually created. However, this is the first time I try pivot table function. It's a pretty convenient and efficient way to create working sheet, automatically. The flexible filter option is also a plus. A little bit challenge is to determine which values or rows should be selected to meet the project goal appropriately, and which chart could best show the expected trends and solution. That requires the deepen understanding about the data and the project background.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

    The chart of outcomes based on launch date is created as below. The theater outcome counts over twelve months clearly indicate that early summer, especially May is the period when to launch a campaign and to achieve most sucessful outcomes. Oppositely, the campaigns launched in December run out with lease successful outcomes, but most failed outcomes. Probably May would be a best time to launch new campaigns.

    ![Outcomes vs date_Image](https://github.com/hankai26/Campaign_Fund_Analysis/blob/main/resources/Theater_Outcomes_vs_Launch.png)

- What can you conclude about the Outcomes based on Goals?

    The chart of outcomes based on goals is also prepared. The trend shows that the successful rate is highest when the goal amount's less than 1,000. The successful rate trend generally drops when funding goal increases to the range of 25,000 to 29,999. When the goal is higher than 25,000, the trend looks more complicate showing another successful peak when goal's between 35,000 and 45,000, but with significant decrease when the amount's above 45,000. The highest failed outcome rate occurrs when the goal is set up in the range of 45,000 and 49,999.

    ![Outcomes vs goal_Image](https://github.com/hankai26/Campaign_Fund_Analysis/blob/main/resources/Outcomes_vs_Goals.png)

- What are some limitations of this dataset?

    1. The Kickstarter consists of 4,114 data points. However, there're only 1,369 counts in the parent category of theater for successful, failed and canceled outcomes over all countries. The data samples are not adquate enough to develop a strong conclusion. Similarly, the total number of outcome counts excluding live campaigns is 1,046 for the subcategory of plays, which could be a small sample size comparatively.
    2. Within the available data, it is expected to examine or eliminating the outlier that are not representative of the useful data. The analysis would be more accurate and efficient if the central tendency, variance, and standard deviation were measured and evaluated.

- What are some other possible tables and/or graphs that we could create?

    Based on the limitation discussed above, we could further develop the analysis using box plots, to examine the data validation. The outlier should be removed prior to analyzing the relationship between outcomes and launch date as well as fund goals.

    ![BoxPlots_Goals](https://github.com/hankai26/Campaign_Fund_Analysis/blob/main/resources/BoxPlots_smallersize.PNG)



