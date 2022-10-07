# Kickstarting with Excel

## Overview of Project

### Purpose
Louise has created a play named Fever that is very close to reaching its fundraising goal. She wants to understand how different campaign goals and launch dates have an impact on the success, failure, and cancellation of previous Kickstarters. The purpose of this analysis is to use the dataset provided to visualize how different Kickstarter launch dates and funding goals effect their campaign outcomes.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
To visualize how Launch date impacted Kickstarter success, a pivot table was created and used to filter the data. The line graph below displays the Kickstarter outcomes (successful, failed, or canceled) of theater projects, based on the month the campaign was launched. 

### Analysis of Outcomes Based on Goals
To compare the outcomes of Kickstarter goals, the data was divided into specific dollar ranges. The range would begin from anything less than $1000, continuing in even intervals (Ex: $1,000 to $4,999), and ending with any fundraising goal greater than $50,000. The amount of successful, failed, and canceled campaigns was calculated based on these different ranges. The campaign outcomes were then converted to percentages, and a line graph was created to display how the different outcomes were affected based on the range of their fundraising goal.

### Challenges and Difficulties Encountered
During my analysis, I was in the process of learning Excel functions while applying what I learned to the data. This hands-on learning was effective in encouraging me to discover new ways on how to utilize excel functions to save time, but also enlightening in the mistakes I made along the way. Specifically, I learned how to save time by copying formulas across rows and not just columns, but I did not know the importance of using the “$” symbol to keep my column data from changing. This was mostly an Issue with the =COUNTIFS formula, as I had to use that formula repeatedly across many columns and rows, and I ended up having to manually go back and change all the columns data from “D:D” to “$D:$D”, so that the letter wouldn’t shift from “D:D” to “E:E” when I transferred the formula across rows.

## Results
Two conclusions can be drawn from the “Theater Outcomes Based on Launch Date” chart:
1)	Theater outcomes have the highest rate of success when they are launched during the month of May. Louise should consider launching her play Fever sometime in May to maximize her chances of success.
2)	December has the lowest chance of success for theater outcomes, and the chances of success are almost evenly matched with the chance of failure during that month. Louise should avoid launching her play in December to avoid possible failure of the project.
When examining the “Outcomes Based on Goals” chart, we can conclude that Kickstarter campaigns with a lower fundraising goal have a higher likelihood of success than those with much higher fundraising goals. The chart displays chances of success decreasing and the chances of failure increasing as the fundraising goals get higher. The only exception being the fundraising goals between $35,000 and $40,000.
One limitation with the current analysis is that there’s no outlined explanation for why certain outcomes result in failures. We know by looking at the “Outcomes Based on Goals” chart that a Kickstarter’s chances of success decrease as the fundraising goal increases, but we don’t know why this happens, or why there’s an exception to this trend in certain parts of the chart. We also don’t know if there are any factors we could add or remove to the fundraising goal that would change the outcomes of failure, to an outcome of success. 
If Louise was interested in further analysis, we could create a new graph or table depicting the outcomes of the Kickstarter based on which country she wants to show her play in. If she wants to host the play in multiple countries, we could filter in the specific ones she’s considering, or if there’s a specific one, then we can focus on the outcomes based solely on that country. We can evaluate the trend of pledged donations based on country, the amounts of backers, and how that influences the success of her play Fever.
