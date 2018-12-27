# LMG-Hackathon
The problem set was to predict that which customer will visit the upcoming new stores . 

## Introduction:
Landmark Group and hackerearth presents an amazing opportunity to showcase one's analytical abilities and talent.


## Problem Statement
Max is a fashion brand within Landmark Group and has launched certain new stores in the year 2018. The objective is to determine whether an existing customer of Max UAE will shop in each of the new stores.

### Data Details

* **Customer_Demographics:** Customer demographics details for 100k customers 

* **Customer_Transaction:** Customer-Store-Week level transaction details for the last two years

* **Store_Master:** Store attribute details

* **Test_Set:** Submission file at Customer- New Store prediction level. Use this to create an additional column of Prediction tagging each 

* **customer-store:** into a 1 or a 0 for the submission file.



### Evaluation Method
**F1 – Score at Customer Store level in the Test_Set for 1’s (Customers who buy in new stores) .**

### Approach
My approach towards the problem was simple rule based segregation of the customers base and mapping thier corresponding stores on the basis of distance travelled. I had calculated the distance from the new coming stores to all the rest of stores, thereby giving me a proximate periphery of what stores are likely to be visited, on the basis of distance.


### Leaderboard
###### Public LB : 10th Rank
###### Private LB : 10th Rank

#### Link to hackathon
https://www.hackerearth.com/challenge/hiring/LMG-analytics-data-science-hiring-challenge/problems/
