# Regression Modeling of Mothers Age on Child Birthweight


The outcome of the exploratory data analysis was interesting but not realistically beneficial in any way. In my time as an analyst I’ve found that figuring out what is not the answer is part of finding the answer. So, there is nothing groundbreaking, but I was not expecting this either. To sum up my EDA, mother’s age is no real statistically significant predictor of child birth weight (for the variables tested). I feel the only thing I missed during the analysis would have been a multivariate model to find possible correlations and test those further. I really just chose some variables that looked easy to work with, so feature engineering could’ve been handled better by myself. 
Looking into the NSFG data further, I could have looked at other variables that are often part of “stress” to the mother, which could have had an effect on birth weight. These variables may include if the mother worked, religion, insurance, poverty, etc. 
I did not make any assumptions about this data because I have worked with it in the course and was pretty familiar with the data. Had I used other variables, that may not have exact explanations, I may have had to make some assumptions. 
	The biggest challenge I faced was reshaping my data while attempting to fit my model. I kept running into the same error. 
valueerror: expected 2d array got 1d array 
I worked on this for far too long before reshaping both x and y. I think this was a result of the error giving me directions to change to an array. When that did not work I attempted other approaches. My problem was that I was only reshaping one set of data but not the other. I’m not really sure how this portion became such a problem but it was easy after I figured out how “sklearn” wanted the data formatted. 

