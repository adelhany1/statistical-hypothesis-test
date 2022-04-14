# statistical-hypothesis-test
Hypotheses are claims, and we can use statistics to prove or disprove them. At this point, hypothesis testing structures the problems so that we can use statistical evidence to test these claims. So we can check whether or not the claim is valid.

1. Defining Hypotheses
2. 
First of all, we should understand which scientific question we are looking for an answer to, and it should be formulated in the form of the Null Hypothesis (H₀) and the Alternative Hypothesis (H₁ or Hₐ). Please remember that H₀ and H₁ must be mutually exclusive, and H₁ shouldn’t contain equality:

H₀: μ=x, H₁: μ≠x

H₀: μ≤x, H₁: μ>x

H₀: μ≥x, H₁: μ<x
                 
2. Assumption Check
                 
To decide whether to use the parametric or nonparametric version of the test, we should check the specific requirements listed below:
Observations in each sample are independent and identically distributed (IID).
Observations in each sample are normally distributed.
Observations in each sample have the same variance.
                 
3. Selecting the Proper Test
                 
Then we select the appropriate test to be used. When choosing the proper test, it is essential to analyze how many groups are being compared and whether the data are paired or not. To determine whether the data is matched, it is necessary to consider whether the data was collected from the same individuals. Accordingly, you can decide on the appropriate test using the chart below.
                 
                 https://user-images.githubusercontent.com/99558161/163493643-6d415c40-f3a2-4047-923d-3f145de4667d.png
                 

                 

4. Decision and Conclusion
                 
After performing the hypothesis testing, we obtain a related p-value that shows the significance of the test.
If the p-value is smaller than the alpha (the significance level), in other words, there is enough evidence to prove H₀ is not valid; you can reject H₀. Otherwise, you fail to reject H₀. Please remember that rejecting H₀ validates H₁. However, failing to reject H₀ does not mean H₀ is valid, nor does it mean H₁ is wrong.
