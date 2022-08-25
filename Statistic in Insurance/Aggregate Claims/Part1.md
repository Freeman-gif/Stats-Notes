# Part1

Aggregate = [[frequency]] *[[Severity]]
## Aggregate Claims – part 1  
---
We have discussed models for claims frequency and models for claims severity. We are now going to  discuss total or aggregate claims. For this, we will have two models.  

The individual risk model assumes we have a severity distribution for the total claim amount by  individual, $X_i$. The number of insureds is known to be n and they are assumed to be independent. Let T  denote total claims then  
$$T = \sum_{i=1}^{n}\limits X_i$$
E[T] = $$\sum_{i=1}^{n}\limits E[X_i]$$
Var(T) =  $$
\sum_{i=1}^{n}\limits Var[X_i]$$









If the severity distribution is identical then


$$E[T] = nt[x]$$


$$Var(T) = nVar(x)  $$
The collective risk model does the calculation based on a frequency count, N, for number of claims and a severity model, S, for each claim. The claim amounts are assumed to follow identical distributions.  Frequency and severity are independent.  
$$
T|N = \sum_{i=1}^{n}\limits S_i

$$
$$
E[T|N] = E[\sum_{i=1}^{n}\limitsS_i]
$$

Example:  
A bond investor uses an actuarial model to analyze default risk on a portfolio consisting of 450 corporate  
bonds, each with a face amount of $1000. Each bond is the obligation of a separate corporation, and the  
investor assumes that during a given year, the probability of default is 0.005. Bonds are independent. If  
a bond defaults, the amount of loss is uniformly distributed on (0,1000).  
a. Using the individual risk model, calculate the expected aggregate loss and the variance of  
aggregate losses.  
b. Using the collective risk model with a Poisson (2.25) as the distribution for claims counts  
(number of defaults), determine the expected aggregate loss and variance of aggregate loss.
---
## Notes and Ideas:
---
### Key words:
---
#### tags:









	

