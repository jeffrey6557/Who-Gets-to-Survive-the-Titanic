Who-Gets-to-Survive-the-Titanic
===============================

Midterm Project, Harvard Math 156. Chang Liu and Alex Patel

You can view the presentation at http://rpubs.com/jeffrey6557/52266

===============================

**Introduction**

On the silent night of April in 1912, the largest ship afloat RMS Titanic aimed towards New York, sank with more than 1500 lives into the depth of the Atlantic Ocean, which was an enormous shock to the whole world. With only 705 survivors on the ship, about 1/3 of the people onboard, we can’t help but ask the questions: Who gets to survive the daunting nightmare of the night? What are the leading factors associating with survival from the sinking of the Titanic? And are these relationships, if any, significant? We explored the demographics on the passengers and then performed statistical tests on our hypotheses and found some interesting conclusions. 


**Data**

The data is a sample of 1310 passengers from the population size of 1317 so it approximates well the population. The variables of demographics we will be looking at are Age, Gender, and Passenger Class.


**Objective** 
To find out the survival rate or distribution by age, gender, and passenger class by exploring various plots and statistics, and then perform a permutation test, a chi-square test or both to verify selected test statistics.


**Procedure and findings**

**Age**

* The distribution is noticeably right-skewed, with 50% of the sample aging from 20 to 40 years old, although there is clear dip of pre-teen and teenage passengers (for good reason, even in 1912).

* 52% of children and only 36% of adults survived, although there are far less children than adults on the ship. A permutation test shows the survival ratio (1.5 times) of children versus adults is statistically significant.

**Gender**

* 73% of women and only 19% of men are saved despite the fact that the number of men almost doubles that of women. Women are saved 3.8 times more often than men! 

* A permutation test and a chi-square test show that this survival rate is statistically significant and that the gender and survival are highly dependent with a p-value far below 1% threshold.  

**Passenger Class**

* The number of 3rd class passengers is twice more than that of the 1st and that of 2nd class. However, a chi-square test shows that passengers in lower-numbered passenger classes are more likely to have survived the sinking of the Titanic.


**Conclusion**

We have successfully examined that a code of conduct most famously associated with the Titanic holds true: "women and children first"! In addition, we find that the passengers in the 1st passenger class, a proxy for socioeconomic status, are more often saved than their counterparts.

