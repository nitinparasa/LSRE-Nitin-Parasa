###Running Log of Article selection:
First I found out this article [1]
-	I planned to implement the MERTS (A Method for Early Requirements Triage and Selection) technique developed by M. Khurum et al. in their article [1]. 

In this article the authors used established techniques for formulating effective product strategies. Requirements handling is highly important in MDRE perspective and hence a requirements triage and the selection of the ones aligned with a specific strategy.
 
Then I changed to implement this technique [2]

#Reflective Report:

###Article selection:

-	I came across another article which stresses on the prioritisation of requirements. I find this field more interesting in MDRE context and would like to get hands on experience using techniques in this field and contribute my knowledge in the future. 
-	I plan to execute the Cost-Value approach for Prioritizing requirements. The article used for this is written by J. Karlsson and K. Ryan [2].

**Description of Cost-Value Approach:**

-	The Cost-Value approach for requirements prioritisation developed by J. Karlsson ad K. Ryan helps in ranking the requirements by considering two dimensions: 1. Value to the customer 2. Cost of implementing it. In the process of using this technique we would be using the concepts of Analytical Hierarchy Process (AHP) which forms the core part of the technique. A list of steps have to be followed to implement this technique and finally arrive at a prioritised list of requirements. They are: 

1. Inspection on the requirements is done for clear understanding and completeness of the requirements.
2. We use the AHP to find the relative value of the requirements.
3. Then the engineer calculates the implementation costs and relative values of each candidate requirement.
4. Then implementation costs and relative values are formulated and then the requirements are placed in cost-value graph. 
5. Using the graph as an aid the stakeholders prioritise the requirements.

**Implementation Plan:**
I plan to take 3 requirements and carry out this technique. The reason I am taking only three requirements is that being this the first time implementing this it would be clear to execute all the steps involved. Moreover the technique that we are implementing here can be scaled to any number of requirements and just the calculations get a bit tough but the whole process remains the same.

**Execution and Proof of Concept:**
  The requirements gathered are a part of the travel guide website where users can enter the system view various places and add the places they would like to visit in the future into their favourites list which will be stored for each and every user. They are: 
R1: As a user, I must be able to login to the system.
R2: As a user, I want to have a responsive interface so that I have good user experience.
R3: As a user, I want to view a catalog of all places, so that I can get to know of all the places in the selected country. 

Step 1: All requirements are clearly understood and written as per standards.

Step 2: Carry out the AHP process:

Step 2.1: Set up 3*3 matrix.

Step 2.2: Perform Pairwise comparisons: 

|       |R1	|R2	|R3|
| --- |:---:| ---:|---:|
|R1	|1	|3	|5 |
|R2	|1/3	|1	|3 |
|R3	|1/5	|1/3	|1 |
  
Step 2.3: Next we perform the averaging method to determine the eigen values of the matrix.

|R1	|R2|R3|
|---:|---:|---:|---:|
|R1|	0.65|	0.69|	0.55|
|R2|	0.21|	0.23|	0.33|
|R3|	0.13|	0.08|	0.11|
	
Then find the sum of each row in the matrix and divide each element by the number of requirements:
	


|1/3||1.89|
|0.77|
|0.32|
	
|0.63|
|0.25|
|0.11|
	
Step 2.4: Assign the relative value to each requirement basing on the eigen value obtained above.
-	R1 contains 63 percent of the requirements’ total value
-	R2 contains 25 percent
-	R3 contains 11 percent.
Then we find out the result consistency just to confirm if we were able to determine the relative value efficiently.
Next we have to find the Consistency Index: CI = (λmax − n)/(n − 1)   
Multiply both matrices to find the value of λmax.
	|R1|	R2|	R3|
|R1	|1	|3	|5|
|R2	|1/3|	1	|3|
|R3	|1/5|	1/3	|1|


|0.63|
|0.25|
|0.11|

Which results in 
|5.69|
|1.08|
|0.18|




Then divide the first element of the resulting vector by the first element im primary vector.
|(5.69/0.63)=9.03|
|(1.08/0.25)=4.32|
|(0.18/0.11)=1.63|
Then we find the value of λmax as : 
λmax = (9.03 + 4.32 + 1.63)/3 = 4.99

CI = (λmax-n)/(n-1) = (4.99 – 3)/ (3-1) = 1.99/2 = 0.99
Finally we find the consistency ratio 
CR = CI/ RI
RI indices for matrices are as given below:
|1	| 2	|3 	|4 	|5	 |6 |7 	|8       |  9      |10      | 11      |12    |13   |  14  |   15
|0.00 | 0.00| 0.58|0.90| 1.12|1.24| 1.32|1.41|1.45|1.49|1.51|1.48|1.56|1.57|1.59
CR = 0.99/0.58 = 1.7 which is not a good value but is occurs very frequently when people apply this method.

