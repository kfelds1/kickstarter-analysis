# Kickstarting with Excel

## Overview of Project

    Louise is hoping to start a crowdfunding campaign to fund her new play, *Fever* but she wants to know if her expectations for the success of her play are realistic. She is looking for more information on what types of variables impact the outcome of a campaign, so I analyzed data from thousands of crowdfunding campaigns across all varieties, including theatre, technology, film, and more.

### Purpose
    
    The purpose of this specific analysis is to explore the outcomes of a campaign based on launch date as well as goal funding. Is there a certain time of year to launch a campaign to ensure that it will be successful? Is there a relationship between the amount of goal funding and the outcome of the campaign?

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

    To determine if there is any correlation between the success of a campaign and the time of year that it is released, I created a Pivot Table that would clearly show the number of successful, failed, and canceled campaigns for each month of the year. This Pivot Table had two filters, one being the Parent Category and the other being the year that the campaign was released. Since Louise is interested in funding her play, the Pivot Table could be filtered for the Theatre category only.
    
![Screen Shot 2022-10-09 at 10 00 51 PM](https://user-images.githubusercontent.com/112633146/194790426-5a092a09-b438-4821-a9b7-bbe9a19160b9.png)

By simply looking at the numbers, there is an evident increase in successful campaigns in the months of May and June. Fortunately, for those looking to begin a theatre campaign, the number of successful campaigns in the data are higher than the number of failed or canceled campaigns. This observation can be seen more clearly in a line chart.

![Outcomes Based on Launchdate](https://user-images.githubusercontent.com/112633146/195211541-b6b094eb-526a-4537-80ec-a4fbe4ddfe32.png)

It is important to note, however, that in the month of December, there were only two more successful theatre campaigns than there were failed campaigns. In general, in the last several months of the year, the gap between successful and failed campaigns decreases, indicating that there are more failed campaigns and less successful ones. It is in Louise's best interest to launch her campaign in the middle of the year, where she has a higher likelihood of success.

### Analysis of Outcomes Based on Goals

    Another key variable to analyze is the campaigner's goal funding amount. Is there any correlation between the amount of goal funding and the success of the campaign? To begin this analysis, I created a table that shows the number of successful, failed, and canceled campaigns, as well as their respective percentages for increments of goal funding. 
    
![Screen Shot 2022-10-11 at 6 52 37 PM](https://user-images.githubusercontent.com/112633146/195212887-aa6c5d61-001e-4de5-88e1-560be3c15838.png)

Since this data is a bit difficult to read, using a visualization technique would help. In this case, another line chart suited the data the best because we could see the percentage of each outcome and its trend for each increment of goal funding.

![Outcomes Based on Goal](https://user-images.githubusercontent.com/112633146/195213193-77248645-a5cd-4dc0-bc46-929d8a72fb0f.png)

The percentage of successful campaigns is higher than the percentage of failed campaigns until the $15,000 to $19,999 increment, and then the percentage of failed campaigns is higher than that of the successful campaigns. However, the percentage of successful campaigns again surpasses that of failed campaigns for two higher increments. It is important to note that there is not much data at the higher increments of goal funding, so it may not be the most reliable to draw conclusions from the data that are already there. From this analysis, it appears that Louise has a higher chance of a successful campaign until her goal funding passes $15,000.


### Challenges and Difficulties Encountered!


## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

    The most evident conclusion to draw from the analysis is that Louise should launch her campaign in the middle of the year because the data show, on average, that those campaigns will have a higher likelihood of success. Another conclusion to draw from this analysis is that there is a downward trend in number of successful campaigns in the latter half of the year; even though there are still more successful campaigns than failed campaigns, Louise's chance of success becomes incrementally lower for each month in the second half of the year.

- What can you conclude about the Outcomes based on Goals?

    Up until $15,000 of goal funding, Louise has a higher chance of having a successful campaign than a failed campaign. If her goal was to have more than $15,000, she should take caution and analyze the other factors that will affect her campaign's outcome. Even though there are trends visible on the graph, the data is very sporadic. The percentage of successful and the percentage of failed campaigns do not show a consistent trend throughout the whole data, so it may be difficult to predict if Louise's campaign will be a success depending on her goal funding.

- What are some limitations of this dataset?

    At some points in the analysis, there was not enough data to draw a solid conclusion. For example, there were not many campaigns that had a high amount of goal funding in general, so forming an argument for these data points is hard to do. There might be another factor affecting the campaign's outcome at this point. There is also a missing data point in the launch date analysis; there is no data for the number of canceled campaigns in the month of October. Working with a dataset that has missing datapoints in more complex analyses is difficult because whether or not to include those specific cases is dependent on the analyis. Sometimes, it may be more favorable to remove those cases entirely from the data, or if there is other data easily accessible that can stand in place of the missing data, that might work as well.

- What are some other possible tables and/or graphs that we could create?

    As we did for the goal funding analysis, I think it would have been helpful to include percentages in the launch date analysis as well. Instead of just looking at the numbers of successful, failed, or canceled campaigns, it is important to look at this numbers relative to each other to get a better sense of the trends of outcomes at different parts in the year. The number of successful campaigns might spike in the middle of the year, but for all we know, the number of failed campaigns might be increasing as well, which would change our analysis.
