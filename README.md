# An Analysis of Kickstarter Campaigns

## Overview of Project
An analysis of Kickstarter projects from 2009-2017 to help gauge the potential success of a play being kickstarted.

### Purpose
The purpose of this project was to analyze data from kickstarter campaigns from 2009-2017 to determine optimal release times, backing goals, expected avg donation levels, etc. to determine the likelyhood of success for a play being succesfully kickstarted. 

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
![Theater Outcomes vs Launch Graph](https://github.com/Tbrecke01/Kickstarter-Analysis/blob/main/Theater_Outcomes_vs_Launch.png)

As shown in the above graph, the highest likelyhood of succesfully kickstarting a theater production is to launch it in the months of June, July or August with a very steep dropoff ocurring in September. July is the most likely start-month for a play to succeed with ~66% of theater productions suceeding in this month. By contrast, January is by far the worst month to launch a new theater kickstarter with 50% of all such projects either failing or beig cancelled.

### Analysis of Outcomes Based on Goals
![Outcomes_vs_Goals Graph](https://github.com/Tbrecke01/Kickstarter-Analysis/blob/main/Outcomes_vs_Goals.png)

As shown in the above graph, the highest likelyhood (upwards of 70%) of a play suceeding are when their goals are below $10,000. Once a theater productions kickstarted goal exceeds $10,000 there is a nearly 20% drop in it's likelyhood of suceeding and this number continues to gradually fall, with theater kickstarters being more likely to fail to succeed once their goal exceeds $20,000. Once a plays goal exceeds $30,000 there is another steep dropoff where the likelyhood of sucess falls to sub 30%.

It is worth acknowledging that there appears to be an uptick in succesful kickstarters whose goals are between $35,000 and $44999. These were determined to be outliers, and the uptick in success more closely attributed to the presence of notable playwrites and actors sponsoring the kickstarter than anything else. If you do not fall into the category of notable playwrite or actor, this shouldn't be considered.

### Challenges and Difficulties Encountered
One notable difficulty was that the examples provided on Canvas did not match up with the results I found. This was determined to be because the launch-dates on Canvas differed from the launch dates of my dataset. I vereified with the third party of Venkata (TA) that this was not an issue.

Another issue encountered was that, in order for my files to fit on Git, some sheets had to be removed from my excel. This resulted in the 'Descriptive Statistics' sheet to get corrupted after analysis. It was kept in the sheet to show analysis was done, so please disregard its current view.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
The vast majority of succesfully kickstarted plays (and plays in general) launch in the summer months of June, July and August, so I would recommend launching in this timeframe (July in particular). January is the worst month by far to succesfully kickstart a play and should be avoided at all costs.

- What can you conclude about the Outcomes based on Goals?
The highest likelyhood (~73%) of a play being succesfully kickstarted are when it's funding goal is below $10,000, so I would reccommend this as the maximum goal for any kickstarted play. If this is not possible, I would strongly encourage the goal to be below $20,000 as this is the cutoff where kickstarted plays are more likely to fail than suceed.

- What are some limitations of this dataset?
This dataset includes several succesful high-goal kickstarters that would seem to indicate another 'sweet spot' for kickstarted plays with goals between $35,000 and $49,999. Upon further analysis however, it is clear these plays are outliers and their success due to numerous other factors (such as notable actors or playwrites sponsoring them) and thus should not be taken into account. Furthermore, this data takes into account all kickstarted theater projects globally. Since most plays are focused on a local audience, more analysis based on local countries is encouraged.

It is also worth noting that example analysis of this data was provided on Canvas, but that the final product of my analyis did not match with the pictures provided by Canvas. This would be due to Canvas having the launch dates of the plays altered compared to the dataset I was working with. It is recommended a third party verify the launchdates of my dataset before utilizing my recommendations.

- What are some other possible tables and/or graphs that we could create?
As noted above, the included graphs are focused on all kickstarters globally rather than locally, which does not fit how most plays behave. I would suggest including more graphs and tables focused on individual countries to alleviate this. I would also include additional graphs and charts focused on end-date and length of campaign, to see how these values affected kickstarter campaigns to further increase likelyhood of success.
