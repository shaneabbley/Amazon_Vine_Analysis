# Amazon_Vine_Analysis

### Background
In this module we analyzed the effect of Amazon Vine on review quality and quantity. Amazon Vine is a required review service for amazon products. We used Pyspark, AWS, and Postgres SQL to clean and upload the amazon review data to a database. We then analyzed the results using Pandas.

### Results
![Have Vine](https://github.com/shaneabbley/Amazon_Vine_Analysis/blob/main/Resources/VineYes.png)
![Do Not Have Vine](https://github.com/shaneabbley/Amazon_Vine_Analysis/blob/main/Resources/VineNo.png)
![Calculations](https://github.com/shaneabbley/Amazon_Vine_Analysis/blob/main/Resources/Calcs.png)
#### These figures show our dataframes for the reviews with and without Amazon Vine, as well as the calculations we performed on the dataframes.

* Vine
  * 59 total reviews
  * 34 five star reviews
  * 57.6% of reviews had five stars

* No Vine
  * 13480 total reviews
  * 7678 five star reviews
  * 60.0% of reviews had five stars

### Analysis
Although the percentage of five star reviews are very similar between Amazon Vine users and non Amazon Vine users, two other flaws in our experiment were observed. Firstly, we should have analyzed data across all amazon purchases instead of solely on instruments. Analyzing across one product axis increases our risk of error. The other major flaw with this experiment is that the sample size of Amazon Vine user reviews is much too small. A total of 59 reviews is not going to be substantial enough to draw true conclusions. I did not notice any positivity bias from Amazon Vine reviewers because the five star review percentage is actually higher in non Amazon Vine reviewers. That being said, we did not analyze enough Amazon Vine reviewer data to say with certainty.
