# Basic Statistics_Level 2 Set 2
**Topics: Normal distribution, Functions of Random Variables**
**1.	The time required for servicing transmissions is normally distributed with  = 45 minutes and  = 8 minutes.
The service manager plans to have work begin on the transmission of a customer’s car 10 minutes after the car is
dropped off and the customer is told that the car will be ready within 1 hour from drop-off.
What is the probability that the service manager cannot meet his commitment?**

**A.	0.3875   
B.	0.2676   
C.	0.5   
D.	0.6987**


Ans:  B –> 0.2676  
          The servicing transmission will begin after 10 min of drop off so 45+10 = 55 min which will now take more than the usual time so new µ = 55 min.
           The probability that it will now take more than 1 hour to complete 
µ = 55 min
σ = 8 min
![image](https://github.com/HemalathaVel/Basic-Statistics_Level-2-/assets/154992818/e6947c4f-dc6e-48a7-9e17-65fb3dbffbe1)


**2.	The current age (in years) of 400 clerical employees at an insurance claims processing center is
normally distributed with mean  = 38 and Standard deviation  =6. For each statement below, please specify True/False.
If false, briefly explain why.
A.	More employees at the processing center are older than 44 than between 38 and 44.
B.	A training program for employees under the age of 30 at the center would be expected to attract about 36 employees.**


Ans:
A.	False.
   Because the probability for employees at the processing center and more than between 38 and 44 than older than 44.
Mean µ = 38
Standard deviation σ = 6


![image](https://github.com/HemalathaVel/Basic-Statistics_Level-2-/assets/154992818/7424b10d-4438-4f5c-80d3-f9d773648d26)


![image](https://github.com/HemalathaVel/Basic-Statistics_Level-2-/assets/154992818/0e20912b-ead6-4843-b27f-70c77e34645f)

B.	Ans –> True.

![image](https://github.com/HemalathaVel/Basic-Statistics_Level-2-/assets/154992818/560f045f-edda-43cd-a726-cb6b88005566)


**3.	If X1 ~ N (μ, σ2) and X2 ~ N (μ, σ2) are iid normal random variables, then what is the difference between 2 X1 and X1 + X2? Discuss both their distributions and parameters.**     
 
 
 Ans:  
Given:
X1 ~ N (µ, σ2) 
X2 ~ N (µ, σ2)
Where X1 and X2 are independent and identically distributed (iid) normal random variables.


1.	Difference between 2X1 and X1 + X2:
2X1 = Scaling a normal random variable by a factor of 2.
X1 + X2 = Sum of two independent normal random variables.


2.	Distributions:
a.	2X1:
When you scale a normal random variable by a constant (in this case, 2) the mean is also scaled by that constant, but the variance is scaled by that constant, but the variance is scaled by the square of that constant.
Mean: E[2X1] = 2µ
Variance: Var (2X1) = (22) σ2 = 4σ2
Therefore, 2 X1 ~ N (2µ, 4σ2)


b.	X1 + X2:
The sum of two independent normal random variables is also normally distributed.
Mean: E (X1 + X2) = µ + µ = 2µ
Variance: Var (X1 + X2) = σ2 + σ2 = 2σ2
Therefore, X1 + X2 ~ N (2 µ, 2σ2)


3.	Discussion:
•	Both 2X1 and X1 + X2 are normally distributed, but with different parameters.
•	2X1 has a greater spread compared to X1 + X2 because its variance is 4 times that of X1 + X2. This is evident from their variances: Var(2X1) = 4σ2 and Var (X1 + X2) = 2σ2
•	The mean of both distributions is the same: 2µ. However, the spread around the mean is different due to the variance.
•	In summary, while both random variables have the same expected value(mean), they differ in terms of variability, with 2X1 being more spread out compared to X1 + X2.


**4.	Let X ~ N (100, 202). Find two values, a and b, symmetric about the mean, such that the probability of the random variable taking a value between them is 0.99.** 

**A.	90.5, 105.9 
B.	80.2, 119.8 
C.	22, 78 
D.	48.5, 151.5 
E.	90.1, 109.9**
     
Ans:
print("The two values of a and b, symmetric about the mean, are such that the probability of the random variable taking a value between them is 0.99:",np.round(stats.norm.interval(0.99, loc = 100, scale = 20),1))
 ![image](https://github.com/HemalathaVel/Basic-Statistics_Level-2-/assets/154992818/2e1ae741-b9cd-4d42-a436-d91391b4349d)

   The two values of a and b, symmetric about the mean, such that the probability of the random variable taking a value between them is 0.99. option D (48.5, 151.5)


**5.	Consider a company that has two different divisions. The annual profits from the two divisions are independent and have distributions Profit1 ~ N (5, 32) and Profit2 ~ N (7, 42) respectively. Both the profits are in $ Million. Answer the following questions about the total profit of the company in Rupees. Assume that $1 = Rs. 45

A.	Specify a Rupee range (centered on the mean) such that it contains 95% probability for the annual profit of the company.

B.	Specify the 5th percentile of profit (in Rupees) for the company

C.	Which of the two divisions has a larger probability of making a loss in a given year?**

  
  Ans:
A.	Rupee ranges in between Rs. 99 million to Rs. 981 million Rupees, 95%of the time for the Annual Profit of the Company.
B.	The 5th percentile of profit for the company is Rs. 170 million.
C.	The Division of 2 (Profit2 ~ N(7,42) has a large probability of making a loss in a given year.











