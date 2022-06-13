# Kickstarting with Excel

## Overview of Project

### Purpose
Louise’s play Fever came close to its fundraising goal in a short amount of time. Now, she wants to know how different campaigns fared in relation to their launch dates and their funding goals. To assist Louise in making decisions involving future kickstarter campaigns the following analysis was done analyze the sampling of kickstarter data, specific to plays, to provide visuals of how different campaigns fared with their outcomes focusing on their goals and launch dates.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
![image_name](resources/Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals
![image_name](resources/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered
While building and analyzing the Outcomes vs Goals, my graph was not appearing as expected.  Upon initial review of my "Countifs(...)" functions they appeared correct, so I searched Google to review how the criteria commands should be written.  My initial assumption was that "Live" campaigns were supposed to be included with the "successful" totals. After consulting a few different web pages regarding Excel "Countifs" functions and testing including the "live" records this was found to not be the issue.

I returned to my own functions and worked through each set of criteria.  The resulting issue was finally determined to be due to how the criteria needs to be written regarding a number within a range such as "1000 to 4999". Verfiying the required ranges and functions logic resulted in the expected output being reached.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
  - Kickstarters, for plays, that are launched between May and June are the most likely to be successful.
  - Kickstarters, for plays, that are launched in December are the most likely to fail.

- What can you conclude about the Outcomes based on Goals?
  - Kickstarters with goals set less than 5000 have the highest percentage of success.

- What are some limitations of this dataset?
  - The data 

- What are some other possible tables and/or graphs that we could create?
  - Providing a table of Measures of Central Tendency along with its corresponding box and whisker plot based upon the month(s) with the best success rate, could assist Louise to see where her goal should be depending on when she plans on starting her next campaign.
