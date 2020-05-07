# Social Media Campaign Analysis

The dataset is a sample of the company’s social media ad-campaign. The company ran three different campaigns and had numerous different advertisements under these three campaigns. The company segmented its customers based on age, gender and interest. It then recorded the response of customers like Clicks, Impressions, Conversions, etc., to validate the effectiveness of a campaign.
The analysis focused on 2 main objectives, i.e., to increase the brand awareness by driving more traffic to the website and increase the number of reservations made through the website. Hence, for the project I would be focusing on the some of the key metrics like Total Conversion Rate (TCR), Approved Conversion Rate (ACR), Cost per Click (CPC), Click Through Rate (CTR), Approved Cost per acquisition (ACPA) and Total Cost per acquisition (TCPA). Using the results of these metrics, I identifed the most effective marketing campaign. 

## Data Source
[Kaggle - Sales Conversion Optimization Dataset](https://www.kaggle.com/loveall/clicks-conversion-tracking)

## Excel Analysis

Performed an analysis in Excel through Pivot Tables and created different KPIs. The data is segmented based on Age Group, Gender and Campaign Ids. Above mentioned metrics are then used on provide an analysis of the most effective campaign based on these segments. 

## R Analysis

Performed analysis in R looking at different variables, checked for duplicates (Ad_ID ), and created KPIs as mentioned above. 
Built the regression model in R, trying to see if there is a causation between predictor variables (xyz_campaign_id, Age, Gender, Spent) and Outcome Variables (Approved Conversion, Total Conversion) simultaneously, to see which variables are important for the company in understanding their areas of improvement. For further analysis,  created 3 interaction terms: (1) Age & Gender, (2) Age & Spent,  (3) Gender and Spent. Consequently validated the result obtained from the model through linear hypothesis testing. 



 
