Analysis of the dynamics between emotions and behaviors in the Brazilian context
---


This code was developed to calculate the dynamics between affect and behaviors. It computes three different types of calculations: The first one calculates the probability of an emotion to be the reason for the onset of a behavior. The second one calculates the opposite, i.e., the probability of a behavior to be the reason for the onset of an emotion. And, the third one calculates the co-occurrence probability, i.e., the probability of a given behavior and a given emotion to occurr at the same time. Unlike other open-source code, this code is designed to:

1. Calculate the adjusted L metric;
2. Apply a t-test to calculate the statistical significance of the results considering all students;
3. Apply the p-value adjustment calculation for multiple tests, considering the Benjamini/Hochberg (BH) method;
4. Print calculated statistics in tabular form;
5. Compute the dynamics between affect and behaviors 
6. Compute the dynamics between behaviors and affect  
7. Compute the co-occurrence between behaviors and affect
* Items 5, 6, and 7 are based on calculated statistics, considering only transitions reported as significant after p-value adjustment based on BH method; Also, these items include the analysis when considering the students gender.


---
**Important:** This code is part of the Doctorate Dissertation of Felipe de Morais.
