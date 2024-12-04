# <span style="color:blue">A/B Testing - Facebook</span> <img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAOEAAADhCAMAAAAJbSJIAAAAclBMVEU6VZ/////p7PR8jLzz9fkwTpySn8czUJ2ElMItTJs7WKOpss+msNAnSJnK0eT6+v2Xps3f4+9cca5KY6fU2upSaalDXaVme7SKmcScqMvP1OTj5vDs7/XGzeIiRZhZca+1vtqxutW+x+B2h7mAjrxugLacEYxHAAADBklEQVR4nO3baXLiMBBAYQdsFDkGwr4MJEAy97/iMPmdOLJUortV7x3Apa8Mkhe5qoiIiIiIiIiIiIiIiIiI1Oecaxrfm5MeY3TOT5vtZvexP3S97Y0SfbM8HBeLP6NTPe/t6TyVHmtE/u29W9Tzp6Bm5oSuWnanMJxJoWt3lwE8e0K3G3T+zAn9/e830GdL6J/Xg32mhO516A/UltC1L4HLg1GhW52jfGaEbjd8ijEldMtRLNCG0K1iJlFLwvYWDzQhdC8JQAtCP6nLFjYf8bOMCaHbzJKA+oXVPg2oX7hJWChMCN0kEaheuI26nzAk9F0qULuwTQYqFzapE6l64fRYunCVdL1mQNjs4x5c2BH62CcXZoSb6EcXRoTuOXm5v3dULPTdgL9hfbwcXr9rrPj9oQ9+B1PPxtXU++a7FAOrJnSiWY9VO36uDbz3va0a6aFGtgq7orlsbZ7A+1T6HnTzO9tYBQY+yT99mAVWLugh27WVHmd8bhwgHBk+hWHC40Z6mAkFCW9WF4r/BQlfvPQwEwoR1ofSz2E9Qag5hAj1hxCh/hAi1B9ChPpDiFB/CBHqDyFCJbmf80FC33OEr4R9y+ef++x+3xE1v3z2HOEr2XdTPuk7g7Bkf8YPENZvpQvXshuGHiC8yL6ceoDwtfj/ofCmrwcIl8ULV6LABwhP29KFa1ngA4S34oVd8cJJ8ULpTWH5hbvShSfhBT+/cC29sS+78Cx8SZNfeBW+pMkvPAgD8wsn0juIsws/SxeO/pYuXOyEgdmF8l+b5BbepJfD7EL5z01yCzvxnfyZhXP5d2+ZhSfx5TC3cCG+HOYWrqXvDrMLZ+KLRW7hWdp3F16zCm/ii0VVtT2F7cVwPUeQ1v1WE7YXQ3qYCRWyn6YnhAj1hxCh/hAi1B9ChPpDiFB/CBHqDyFC/SFEqD+ECPWHEKH+ECLUH0KE+kOIUH8IEeoPIUL9IUSoP4QI9YcQof4QItQfQoT6Q4hQfwgR6g8hQv0hRKg/hAj1hxCh/hAi1B9ChAP6B1ndUcZ6wYWaAAAAAElFTkSuQmCC" align='right' style="width: 80px;"/>



 

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