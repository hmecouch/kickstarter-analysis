# Analysis of Kickstarter Data
## Overview of Project
For this project I sorted and extracted data from a large sample of crowdfunding campaigns in order to draw logical conclusions.
### Purpose
The purpose of this analysis is to give Louise a visualization of crowdfunding data that shows how similar crowdfunding campaigns fared in relation to their launch dates and funding goals. This should give Louise an idea of whether there are better crowdfunding launch dates for meeting or exceeding funding goals. The analysis will also show her which funding goals are most successful for plays. She will be able to use all of this information to launch more successful crowdfunding campaigns for future projects. 
## Analysis and Challenges 
I started with creating a visualization for launch dates data. To do this I created a pivot table with outcomes for the columns, launch dates for the rows and the outcomes for the values. The values show the number amount of successful, failed, and canceled campaigns. I also added years and parent category for filters so that I could make the table only show me data from specific years and specific categories. I chose to filter the table to only show the theater results because that's what Louise was funding for. Although the pivot table gives a good visualization of the data, I then went a step further and made a line chart to easily identify which months had the most success. ![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/114922260/195739483-7587045f-e637-4a49-8a1c-c3ec17506df0.png) 
After this I showed the data of the outcomes based on goals. To do this I made a new sheet and created a table with goal ranges in the rows and columns being number successful, number failed, number canceled, total projects, percentage successful, percentage failed, percentage canceled. To extract the data I needed to fill the numbers columns I had to use the countifs() function, for the data in the total projects column I used the sum() function, and for the percentage columns I divided the numbers columns by the totals and switched the column to percentages. Then I made a line chart to display this data. ![Outcomes_vs_Goals](https://user-images.githubusercontent.com/114922260/195739607-1d57401a-b6f9-4339-a5b1-fab52864bf4d.png). 
The only challenge I encountered for this was trying to get the goals chart to display the percentages on the y-axis. To figure this out I just simply used google.
### Analysis of Outcomes Based on Launch Date
Based on the graph I created with my data we can conclude that the best time of the year to launch a successful theater campaign is from late April to July. This time frame has the highest percentages for success. The worst time to launch would be September through December. 
### Analysis of Outcomes Based on Goals
Based on the graph of the goals data we can conclude that as the funding goals begin to get higher they tend to be less successful in meeting said goal. There are a few exceptions to this conclusion but they're outliers skewing the data.

  


