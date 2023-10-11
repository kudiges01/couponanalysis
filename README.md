# Will a Car Driver Accept or Reject the Coupon

This repository contains an analysis of data about bar, restaurant and coffee house coupons sent to car drivers. This dataset is part of the UCI Machine Learning repository and was collected via a survey on Amazon Mechanical Turk. The analysis determines the likelihood of a driver accepting a coupon based upon various parameters such as "driver age", "kind of passenger in the car with the driver", "driver occupation" etc.

## Technologies used for Analysis

 - **Jupyter Notebook** https://jupyter.org/
 - **Python Pandas** https://pandas.pydata.org/
 - **Seaborn** https://seaborn.pydata.org/
 - **Matplotlib** https://matplotlib.org/
 - **Plotly Express** https://plotly.com/python/plotly-express/

## Coupon Acceptance Rate

Analysis and plotting of the data using Seaborn shows the **Coupon Acceptance Proportions** for each type of coupon (Figure below).  **Bar Coupons** have the lowest acceptance rate of 41.2% while **Carry Out & Takeaway Coupons** have the highest acceptance rate of 73.6%. **Bar Coupons**, **Coffee House Coupons** and **Restaurant (20-50) - Expensive Restaurant Coupons** have a lower acceptance rate in comparison with other two categories (**Restaurant (<20) - Cheaper Restaurants** and  **Carry Out & Takeaway Coupons**). 

![alt text](https://github.com/kudiges01/couponanalysis/blob/main/images/couponproportion.png)

## Bar Coupon Analysis

The analysis shows that to maximize coupon acceptance rates, targeting the coupons to the following audience helps.

 - Drivers who are likely to go to a bar more than once a month
 - Drivers who are primarily between the ages of 21 and 31
 - Drivers that do not have kids as passengers
   
The Seaborn plot below shows that the acceptance rates for bar coupons is significantly higher at 72.3% for these drivers. So, this specific targeted approach of sending coupons can increase the Bar Coupon acceptance rate from the original 41.2% to 72.3%.

![alt text](https://github.com/kudiges01/couponanalysis/blob/main/images/Barcoupon.png)

## Restaurant(20-50) Coupon Analysis

The analysis shows that to maximize coupon acceptance rates, targeting the coupons to the following audience helps.

 - Drivers who are likely to go to an expensive restaurant more than once a month
 - Drivers who had passengers in their car
 - Drivers who were between the ages of 21 to 46
 - Drivers who had incomes of 87500 and higher

The Seaborn plot below shows that the acceptance rates for Restaurant(20-50) coupons is significantly higher at 82.4% for these drivers. So, this specific targeted approach of sending coupons can increase the Restaurant(20-50) Coupon acceptance rate from the original 44.7% to 82%.

![alt text](https://github.com/kudiges01/couponanalysis/blob/main/images/Restaurant.png)

## Future Work

The Coffee House coupons can also be analyzed to glean how the acceptance rate can be maximized. In addition, machine learning algorithms can be applied to this data to make more granular predictions on coupon acceptance.

