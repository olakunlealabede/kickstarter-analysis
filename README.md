# kickstarter-analysis
Performing Kickstarter analysis to uncover trends
This analysis centers on Louise's Play Fever campaigns which reveals how different campaigns fared in relation to their launch date and their funding goals. Kickstarter dataset are thoroughly analyzed, campaign outcomes are then being visualized based on their launch dates and their funding goals.
## Ananlysis and Challenges
Louise's Play fever campaign was analyzed under Theater outcomes based on Launch date in which Pivot table fields was used to create a new dataset to visualize campaigns on launch date. Firstly, parent category and years were filtered in which only Theater outcome was selected under the filter. The outcomes was then labeled under the column axis. Date created conversion was assigned to row axis and the dates were converted into monthly basis. It was very challenging to convert the years into months to visualize the Theater outcomes based on launch date. Finally outcomes was placed into "values" which becomes count of outcomes.


<img width="363" alt="Based on launch date" src="https://user-images.githubusercontent.com/89113627/133306658-fc908b11-559f-43e7-aec3-93bca88c09fd.PNG">

A line chart with marker was selected to visualize the Theater outcomes based on Launch date.
The table and graph for Outcomes based on goals was also created which shows a range of set of goals from less than 1,000 to greater than 50,000 with interval of 5,000 on their funding goals. An analytical function of COUNTIFS was used to generate number for successful outcomes, failed outcomes, and canceled outcomes in a  new worksheet. It was revealed during the analysis that canceled outcomes generate no point through out the dataset. Then percentage were computed for successful, failed, and canceled outcomes.
A line chart was then drawn from the table to show outcomes based on goals.


<img width="392" alt="Outcome Base on goal" src="https://user-images.githubusercontent.com/89113627/133306260-83ea4f96-02a7-4caa-ae68-4582b77562b9.PNG">


## Conclusion
In conclusion, the campaign was successful in all the months under Theater outcomes based on Launch date. The month of May and June also recorded significant increase in outcomes as compared to other months.
Meanwhile, outcomes based on goals shows less funding goals for successful outcomes compared to failed outcomes. It is noted that when less than 20,000 funding goals were raised, Louise's Play Fever campaign recorded more successes than when large funds were being campaigned for. Therefore, campaigns for outcomes based on goals should focus on less funding rather than huge funding. Large funding is considered as a limitation for this campaign.
Finally, there are other possible table and/or graphs that can also be created which are as follows:
Music Outcomes based on Launch date
Film and Video Outcomes based on Launch date
Technology Outcomes based on Launch date
