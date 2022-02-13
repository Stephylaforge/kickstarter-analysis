# An Analysis of Kickstarter Campaigns
##Preforming analysis on Kickstarter data to uncover trends using spoecific data to find out important information regarding the campaigns.
###Purpose
The purpose of this anaylsis on the campaings to provide results from the outcomes based on launch date and based on goals.
##Analysis and Challenges
The Analysis was taking the Outcome category and seeing two different types of results that can be beneficial to Louise or other campaigns. This information based from outcomes, date created and goals all tell a different story about whether the plays were successful, failed. Or tell a story about the theater and what months had the most successful or failed campaigns.
### Analysis of Outcomes Based on Launch Date
The first analysis is the outcomes based on launch dates. I took the data from the Kickstarted data sheet and created a Pivot tabled filtered by Parent Category Theater and filtered by the date it was created. The launch date's were converted in excel using Unix time stamps that excel converts into dates. That column was then used to interpret the outcomes based by dates. 
### Analysis of Outcomes Based on Goals
The second Analysis based on goals was to take the filters from the Goals column in Kickstarter and filter the plays by 'successful', 'failed', or 'canceled'. To do this I had to type in the "countifs" equation and add in the criteria from each column in the Kickstarter data sheet. From doing this I came accross some numbers that seemed shorter out of the great vary of data but I realized that the subcategory in plays would play a role in the data and how small and large it was. 
### Challenges and Difficulties Encountered
Some challenges I faced were doing the countifs' equations in excel. Going back n fourth from the sheets was not difficult it was filtering through the equations to make sure they had the right criteria. I tried triple checking if there really were no canceled plays in the goals results from the Kickstarter data but after double checking the equations that was what I concluded based off the data and the results. 
## Results
From the Outcomes based on Launch Date I can conclude that the theater was very successful in the two months of May and June. And the outcomes of successful are much higher than the other two categories.
 To conclude the final outcomes based on Goals I got the results that the campaigns in the subcategory for plays, that had a status of canceled were all zero based on their goal ranges. Second I concluded that the successful and failed categories has higher precents with lower budgets. 
The limitations are that even though this dataset can show trends, outcome dollar amounts, status of failed or success, at the end of the day these are all outcomes based on various data and outcomes and it can show an example for a future campaign but there can be no guarantee that a play with a budget or goal will have the same outcomes as the pervious ones.
Based on the Kickstarter Data there would be another chart that I think could benefit the data. It would be a pie chart that shows the percentages of the successful, failed, and canceled plays based on their goals. Pie charts are beneficial to someone who wants to interpret the data quickly but still get accurate knowledge of the data side by side.
