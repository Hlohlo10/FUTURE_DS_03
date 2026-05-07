# Marketing Funnel & Conversion Performance Analysis
## Future Interns - Data Science & Analytics Task 2 

### Overview 
This project analyzes a real-world bank direct marketing campaign dataset
to identify conversion drop offs, channel performance, and opportunities to
improve lead to customer conversion rates.
The dataset contains 45,211 phone call records from a Portuguese banking
institution, covering campaigns run between May 2008 and November 2010.
The goal was to predict and understand which customers subscribed to a
bank term deposit after being contacted.

### Business Questions Answered
Where are contacts dropping off in the funnel?
Which contact channels produce the highest conversion rates?
Which months are best for running campaigns?
How does call duration affect conversion?
Which customer segments convert the best?
When should the team stop calling a contact?

### Tools Used 
Python -Data cleaning and analysis
Pandas -Data manipulation
Matplotlib -Dashboard and chart creation
VS Code -Development environment

### Key Insights 
1. Overall Funnel
44,920 total contacts made across the campaign
Only 5,255 subscribed - an overall conversion rate of 11.7%
88% of contacts are dropping out of the funnel

2. Best Contact Channel
Cellular contacts convert at nearly 2x the rate of telephone contacts
Building a cellular contact database is the single biggest lever for improvement

3. Best Months to Call
March, September, October and December convert well above average
May has the highest call volume but converts below average
Campaign resources should be shifted away from May toward Q4

4. Call Duration Impact
Calls under 1 minute convert at under 1%
Calls over 5 minutes convert at over 40%
Duration is the strongest single predictor of conversion

5. Number of Calls
First calls produce the highest conversion rate
After 3 calls, conversion drops sharply
6+ calls produce near-zero conversions — a waste of agent time

6. Best Customer Segments
Students and retired customers convert at the highest rates
Previous successful subscribers convert at over 60% in subsequent campaigns

### Charts 
![graphs campaign](graphs_campaign.png)
![graphs demographics](graphs_demographics.png)
![graphs overview](graphs_overview.png)

### Dataset
 Bank Marketing Campaign Dataset (UCI Machine Learning Repository) from Kaggle 

