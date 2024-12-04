# <span style="color:blue">A/B Testing - Facebook</span> <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTbYQPBnXlJZbTr03Kmti6R-6NmvdsQS5F2Mg&s" align='right' style="width: 80px;"/>
 

**Description of the A/B Testing Analysis:**

Facebook recently introduced a new bidding system called "average bidding"(test group) alongside the existing "maximum bidding"(control group) system. These bidding systems determine which ads get displayed to users based on how much advertisers are willing to pay.

- **Control Group (maximum bidding):** advertisers specify the maximum amount they are willing to pay for each impression. For example, an advertiser might say, I'm willing to pay a maximum of $10 for each impression.
  
- **Test Group (average bidding):** advertisers specify an average amount they are willing to pay for impressions. For instance, they might say, "On average, I'm willing to pay $6 for each impression."

In the dataset, there are the results of these two bidding strategies over the last 40 days to see which one is more effective at getting their ads displayed to the target audience.



The dataset includes the following metrics split in two datasets:
- **Impression:** Number of impressions per ad.
- **Click:** Numbers of clicks per ad.
- **Purchase:** The number of products purchased after the click.
- **Earnings:** Earning after purchase.

**Test Aims:**

The mission is to unearth the most advantageous approach for Facebook. Based on the following burning questions:

- **Maximize Clicks and Purchases:** Which strategy will propel us toward our goal of skyrocketing clicks and driving purchases?
- **Battle of Titans:** Is there a discernible and statistically significant difference between the two bidding options?

The outcome of this AB Test will not just answer our questions but will be the harbinger of a glorious era in our Facebook advertising endeavors. Stay tuned for a transformation that will leave a mark on the digital advertising landscape.


- **Null Hypothesis (H₀):** There is no significant difference in the number of purchases between the control group (maximum bidding) and the test group (average bidding).
- **Alternative Hypothesis (H₁):** Moving to specifying an average amount (average bidding) produce an increase in the average of number of clicks/purchases.

# <span style="color:blue"> Facebook Conclusion</span>

##  <span style="color:blue">Results</span>
For Purchases:
- P-Value: 1.0000
- Fail to reject the null hypothesis (H₀): The means are not significantly different.
- Mean Difference: 31.1500
- 95% Confidence Interval: (-390.0902, 452.3902)

For Clicks:
- P-Value: 0.8248
- Fail to reject the null hypothesis (H₀): The means are not significantly different.
- Mean Difference: -1133.0750
- 95% Confidence Interval: (-4385.4968, 2119.3468)


##  <span style="color:blue">Conclusion</span>
Based on the results, there is no statistically significant difference between the control group (maximum_bidding) and test group (average_bidding) for both purchases and clicks. 

The p-values for both purchases (1) and clicks (0.8248) are well above the typical significance threshold of 0.05, indicating that we fail to reject the null hypothesis in both cases. 

The mean differences and 95% confidence intervals for both metrics overlap zero, further supporting the conclusion that the variations in the test group do not have a meaningful impact compared to the control group. 

Therefore, it would be advisable to refrain from making changes based on this test, as the data does not show a significant improvement or decline in either purchases or clicks.



<img src="https://st.depositphotos.com/1054619/4043/v/450/depositphotos_40435245-stock-illustration-like-button.jpg" align='right' style="width: 100px;"/>