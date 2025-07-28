
### Independent Investigation

**Investigation 1**

One important dimension, what time the highest number of coupons got accepted and which caytegory
For that we can group by time first and then by coupon ( category).
The sum will give us the total number of coupons gets accepted at that time range for that category

 OutcomeFindings/Key Observation(s)
 ----------------
 1. Most of the drivers appears to have accepted the coupons at "Economy" restaurants at 2PM and 6PM.
 2. Coffe house seems to the most popular at all times except 10PM. with highest at 10AM (576)  So better NOT to send coffe house coupomns at 10 PM
 3. Suprisingly bar coupons are being accepted at 7AM. A possinbility to check outliers here?

 Next Steps
 ---------
 1.  Find out correlation between categorical attributes and refine what attributes are most influencing.
 2.  Find out outleiers of why people are bar coupons at 7 AM which is bit unusual.
    
Visual 
----------------
<img width="1772" height="1000" alt="image" src="https://github.com/user-attachments/assets/f9a552a9-5aaf-4f34-b491-f09d1b31ed55" />



**Investigation 2**

Another interesting dimension to see by marital status. who are accepting what and what type of coupons.

 OutcomeFindings/Key Observation(s)
 ----------------
 1. Married partner and Singles appears to be accepting more coupons then Divorced and Widowed.
 2. In this dimension also , expensive restaurants are NOT hot favorites.

Visual 
----------------
<img width="1828" height="1038" alt="image" src="https://github.com/user-attachments/assets/4def3e05-a137-4644-abec-db6a958b2c9a" />

Next Steps
----------
1.  Find out correlation between categorical attributes and refine what attributes are most influencing.
2.  
**Investigation 3**

Compare acceptance rate of those drivers who takes carry out more than 3 times and is married with children

OutcomeFindings/Key Observation(s)
 ----------------
  There appears to be a minor difference in acceptance rates between the two groups

All Others   0.727506
Dimension 1  0.739319
Difference in acceptance rate: -0.0118

Visual 
----------------
<img width="1506" height="1032" alt="image" src="https://github.com/user-attachments/assets/2f110352-a147-4889-9c29-fc8c2c242507" />

Next Steps
----------
1. While there is a very minor gap between All others vs Dimension-1 , find out if we are missing any other crucial params ( just to confirm)
2. If everything looks good, take it to the next level to see which model helps to put it for meachine learning.
   
**Investigation 4**
Show the distribution of acceptance across coupons on a pie chart

OutcomeFindings/Key Observation(s)
-----------------
Coffeshop appears to have highest acceptance folllowed up economy restaurants

Visual 
----------------

<img width="1888" height="720" alt="image" src="https://github.com/user-attachments/assets/76ff8d03-f77a-43ff-8729-3b4313b4c27b" />


**Investigation 5**

Show the distribution of acceptance across coupons on a line chart

OutcomeFindings/Key Observation(s)
-----------------
Young ages appears to have more acceptance then mid ages and old ages.


Visual 
----------------
<img width="1760" height="1150" alt="image" src="https://github.com/user-attachments/assets/49307d34-97a8-4d03-90da-c1f8fd4d6aae" />


**Investigation 6**

Compare acceptance of restaurant coupons when:Passenger = Friends Time = Evening Temperature > 70°F 

OutcomeFindings/Key Observation(s)
-----------------
It seems the driver who go out evening after 6 pm with friends appears to be accpepting more coupons.

Visual 
----------------

<img width="1708" height="1190" alt="image" src="https://github.com/user-attachments/assets/43623662-53c2-4c51-8906-56f03e7bbbeb" />

