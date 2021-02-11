# Paired Sample T-test
This repository will explain about paired sample t-test, the test procedure and how to use it using Scipy library of Python.

## Definition
Paired Sample T-test is s a hypothesis testing conducted to determine whether the mean of the same sample group has a significant difference. The test is commonly used for the following scenarios:
* Measurements of samples before and after treatment – e.g. the max vertical jump of basketball players is measured before and after enrolling in a training program.
* Measurement of samples against two different conditions - e.g. the response time of a patient is measured on two different drugs.

## Procedure
* Determine the hypothesis <br> 
  Null Hypothesis &emsp; &emsp; (H<sub>0</sub>):  &mu;<sub>1</sub> = &mu;<sub>2</sub> <br>
  Alternate Hypothesis (H<sub>1</sub>):  &mu;<sub>1</sub>  &#8800; &mu;<sub>2</sub>  
* Define the significance level &alpha; 
  &alpha; = 0.05 <br> 
* Define the rejection criteria  
  'Reject H<sub>0</sub> if p-value < &alpha;'  <br>
* Perform test statistics <br> 
* Draw conclusion
