# Coupon Acceptance
## Analysis of Coupon data to conclude if coupon offered will be accepted by the given customer.
In this project, I have use python libraries such as pandas, seaborn, and matplot to analyze coupon data.
Data is collected by an external service and provided in the form of a CSV file.
It has several attributes such as
1. Gender
2. Age
3. Income
4. Marital Status
5. Coupon category
6. Driving habits - Urgent or non urgent, Passenger or alone
7. Attribute Y shows acceptance of coupon for the given customer
8. Others

This file can be found under the /data folder.
The analysis has been performed using Python Jupiter notebook and notebook can be found under the root folder.
Plots of the analysis are stored under the /images folder for easy access.

Key Conclusions from the analysis -
1. Bar only coupons had an acceptance rate of < 50%
2. However people who went to bar more than 3 times per month had a much higher acceptance rate
3. Similarly people with kids in the car had a much lower acceptance rate than when no kids in the car
4. I did independent analysis of coupons for cheap restaurant
5. Acceptance rate was significantly higher for drivers that were headed to non urgent destinations
6. Income did not have an impact on acceptance of these type of coupons (for the three brackets that I investigated)
7. When I analysed drivers who went to chear restaraunts more than 3 times, they were offered coffee house coupons that were rejected at a high rate. Instead if those drivers  were given coupons for restaurants the acceptance rate would be far greater
