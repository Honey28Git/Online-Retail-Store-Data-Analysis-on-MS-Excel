This dataset is taken from UCI archives. 

I took the liberty to classify the products sold into categories. I did a data analysis on this calculated RFM Analysis, Cohort Analysis, Forecasted Sales  and calculated the following:
Basic Analysis:
The Total Revenue earned between the timeline December 2010- December 2011 is $82,78,519. 
The Average Order Value is $3,92,732. 
The Top Selling Product is PAPER CRAFT, LITTLE BIRDIE which is from the stationery product category. 
The Average Order Value is $3,92,732.
The negative values in the Revenue is assumed to be a returned value. Which increased the probability of Churn The Churn Rate is 2.26%. Churn is not calculated for this dataset. 

The MoM growth rate is rising during the 1st quarter, steady during the 2nd quarter, and decreasing during the 3rd quarter. 

However, as per the sales forecasting trend, the sales trend seems to show a steady rise through 2012. 

Customer Segmentation:
The customers can be segmented into 2 categories: 
The High Spenders: The customers who are spending higher than 1994.064 are High Spenders as they fit into the top 20% of the Customers
Medium Spenders: The medium spenders are customers who spend lesser than 1994 and higher than 232 dollars.
Low Spenders: The Low Spenders are customers who fall in the bottom 20% and spend less than 232.504 dollars per transaction.

Most of our dataset contains customers who fall in the category of Medium Spenders. There are also low Spenders. High spenders are 488 in number.  

Summary of Churn Risk Segments:	
	
1. High Churn Risk (RFM Score: 1-6 with low Recency)	
Total Customers: 669 customers.	
Interpretation: These customers have the lowest engagement, spending, and recency scores. They are the most likely to churn (leave or stop buying). This segment is small compared to the others, but it represents a critical group that requires urgent intervention. Focus on retention strategies, personalized offers, or re-engagement campaigns to prevent churn.	
	
2. Medium Churn Risk(RFM Score: 7-10)		
Total Customers: 20,041 customers.	
Interpretation: The medium-risk group is the largest, representing the bulk of your customer base. These customers are somewhat engaged but are at risk of becoming inactive. They may need consistent marketing efforts, such as loyalty programs, discounts, or reminders about their recent purchases, to push them toward the low-risk category. Monitoring and targeting this group could prevent a significant number of churn cases.	
	
3. Low Churn Risk((RFM Score: 11-15)		
Total Customers: 13,208 customers.	
Interpretation: This group has the highest engagement levels, indicating that they are frequent shoppers, make larger purchases, and are relatively recent customers. These are your most valuable customers who are less likely to churn. However, it’s important to maintain this relationship through excellent customer service, loyalty rewards, and personalized marketing to keep them in the low-risk segment.	
	
Key Insights:
Distribution of Risk: The majority of your customers fall under the medium-risk category (59% of total customers), which is typical in RFM analysis. About 39% of customers are in the low-risk group, while the high-risk group is relatively small (about 2%). The goal should be to move as many medium-risk customers into the low-risk category as possible.	
	
High Churn Risk Focus: Even though the high-risk segment is small (669 customers), they still represent a significant potential revenue loss if they churn. A more aggressive retention strategy might be required for this group, such as exclusive offers, feedback requests, or re-engagement emails.	
	
Action Plan:	
For High Churn Risk: Immediate re-engagement campaigns such as targeted promotions, customer surveys to understand their concerns, and win-back offers.	
For Medium Churn Risk: Regular engagement through newsletters, exclusive offers, and loyalty programs to keep them active and encourage repeat purchases.	
For Low Churn Risk: Reward loyalty through special discounts or VIP treatment to maintain high engagement and prevent them from slipping into medium or high churn risk.	
	
By focusing efforts on medium-risk customers and converting them to low-risk, as well as managing high-risk customers to prevent churn, you'll likely see improvements in customer retention and lifetime value.

December 2010 Cohort (Largest Cohort):

Count: Started with 28,013 customers, dropping to 3,537 by month 13.
Percentage: Initial drop to 39%, peaks at 137% in month 4, then fluctuates between 80%-144% before dropping to 16% by the final month.
January 2011 Cohort:

Count: Began with 12,050, dropping to 188 by month 12.
Percentage: Starts at 22%, spikes to 120% in month 10, then sharply declines.
February to May 2011 Cohorts:

Count & Percentage: Lower initial counts.
February: Drops after month 2 but rises above 100% in later months.
March: Peaks at 151% in month 3.
May: Peaks at 183% in month 5 before dropping off.
Late 2011 Cohorts (June to December):

Count & Percentage: Smaller initial counts with sharp retention declines.
June cohort: 13% retention by month 2.
September cohort: Starts with 9,433 but sharply declines.
November and December cohorts: Severe drop-offs after the first month.
General Observations:
Retention Trends: Early-month drop-offs are common, with occasional recovery (100%+ retention), but later cohorts (June 2011 onward) show sharp declines without recovery.
Cohort Size: Earlier cohorts (Dec 2010–Mar 2011) are larger, while later cohorts are smaller with poorer retention.
Retention Strategy: Fluctuations in retention suggest intermittent success in reactivating customers, but late-stage cohorts show a need for improved retention.
Recommendations:
Focus on Early Retention: Address the steep drop-offs after the first month to enhance customer retention.

Actual Revenue (2011): The revenue shows fluctuations throughout the year, with peaks in September ($929,356), October ($973,306), and November ($1,126,815).

Forecasted Revenue (2012 - Linearity): The linear forecast predicts a steady increase, starting at $382,228 in January 2012 and gradually rising to $997,525 by December 2012.

Forecasted Revenue (2012 - Seasonality): The seasonal forecast follows a similar upward trend but accounts for seasonal fluctuations, starting at $406,451 in January and reaching $1,015,716 in December.

Key Trends:

Growth Expectations: Both forecast models predict revenue growth, with seasonality providing more accurate peaks, especially toward the year's end.
Seasonal Influence: The seasonal forecast aligns better with historical peaks in revenue, such as in November and December.


![Screenshot 2024-09-07 142258](https://github.com/user-attachments/assets/dda12064-d2d9-41ee-bce6-cc108f5434ec)

If you like the analysis, or would like to offer a feedback, you could send your feedback to honeysam28.97@gmail.com 
