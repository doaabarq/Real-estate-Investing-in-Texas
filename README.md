# Project1 - please review RealEstateTexas for code!
For this project, We had the question Where in Texas has the greatest ROI for Airbnb? 

Based on this we had a few questions:
1)What are the top 20 cities in Texas based on Airbnb Rentals? 
2)Does the amount of  Airbnb’s available affect the Airbnb occupancy rate? 
3)What size house should we buy (based on  bedrooms)?
4)What is the  average occupancy rate per bedrooms? 
5)What is the Average rental income for each bedroom size? 
6)How much does SQFT effect the home cost? 
7)Average home cost per city?

Our process was to start by pulling data for Airbnb from Mashvisor via Rapid API. We took this data and found the top 20 cities based on Occupancy rate. We found taht denton Texas had the highest occupancy rate. We also used this data to find the avg occupancy rate for a studio,one bedroom, two bedroom and three bedroom. 
We found that all 5 of those segments had relatively the same occupancy rate in the 40's with studio having slightly higher at 47.4. However, we also used the data to find avg rental icome per month, we found that 4 bedrooms had a significantly higher at $3,507. For this reason, we took a look at average monthly rental amount and occupancy rates for four bedrooms. We found it interesting that South Padre Island had the highest average monthly rental rate for four bedrooms, but the lowest occupancy rate of four bedrooms. 

Next we used zillow.com via Rapid api to pull 40 properties for the 20 cities (and within a 10 mile radius). We were intersted in taking a look at how accurate the Zestimate is to the price.The t-test results indicate that there is no significant difference between the mean values of the "Price" and "Zestimate" .The t-statistic of 0.33 suggsts that the difference between the means of the "Price" and "Zestimate" , is not very large.The p-value of 0.739 is greater than the significance level of 0.05, indicating that there is no strong evidence to reject the null hypothesis that the means of the price and Zestimate is equal.\

We also took a look at how the SQ footage of a home effects the home cost. We found that there is a 0.52 correlation between price and SQFT. Meaning, there is a slight positive coorelation between square footage and price. So the larger the home, the price will marginally increase. 

Finally, we found the average home cost of the top 20 cities Abilene has the lowest average home cost at $236,850. Whereas, Fredericksburg was the highest average home cost at over $1.4M.

In Conclusion: 
As Abilene, Tx has the lowest average home cost and the second highest occupancy rate at 53%. We found that you would get the highest ROI, if you purchased a home in Abilene. Since the occupancy rate for a Four bedroom is relatively the same as  that as the the others, but the monthly  average rental amount is much higher at $3,507. You should look at purchasing a 4 bedroom home to rent on Airbnb.

We did have a few limitations on this project that should be noted.Airbnb has limited their usage of API and therefore, we had to  rely on a third party Airbnb API to have the correct data for occupancy rate. Addtionally, we only pulled 40 properties for the top 20 cities and suburbs. THen we filtered it down to only the 20 cities. 


